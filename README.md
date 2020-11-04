# FIT3179
<!DOCTYPE html>
<head>
  <meta charset="utf-8">
  <script src="https://cdn.jsdelivr.net/npm/vega@5"></script>
	<script src="https://cdn.jsdelivr.net/npm/vega-lite@4"></script>
	<script src="https://cdn.jsdelivr.net/npm/vega-embed@6"></script>
</head>

<body>  
  <div id="vis"></div>
  
  <script>
    const spec = "bar.vl.json";
  	vegaEmbed("#vis", spec)
    	// result.view provides access to the Vega View API
      .then(result => console.log(result))
      .catch(console.warn);
  </script>
</body>

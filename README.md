<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta http-equiv="x-ua-compatible" content="IE=Edge" />
  <!-- Responsive -->
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="default">
  <title></title>

  <link rel="icon" href="assets/favicon.ico" sizes="32x32" type="image/vnd.microsoft.icon">
  <meta name="description" content="Minimalist">
  <meta name="theme-color" content="#0079c1" />
  <noscript>
    <p>Please enable JavaScript to use this site.</p>
  </noscript>

  <link id="esri-stylesheet" rel="stylesheet" href="https://js.arcgis.com/4.16/esri/themes/light/main.css" />
  <link rel="stylesheet" href="./app/@esri/calcite-app-components/dist/calcite-app/calcite-app.css" />

  <link rel="stylesheet" href="css/index.css">

  <script src="./app/es6-promise.auto.min.js"></script>

  <script type="module" crossorigin="use-credentials"
    src="./app/@esri/calcite-app-components/dist/calcite-app/calcite-app.esm.js"></script>
  <script nomodule="" src="./app/@esri/calcite-app-components/dist/calcite-app/calcite-app.js"></script>
  <script type="module" crossorigin="use-credentials" src="./app/@esri/calcite-components/dist/calcite/calcite.esm.js">
  </script>
  <script nomodule="" src="./app/@esri/calcite-components/dist/calcite/calcite.js"></script>
  <script src="./app/dojo.js"></script>
  <script src="https://js.arcgis.com/4.16/"></script>
  <script>
    require(["Application/init"]);

  </script>
</head>

<body>
  <div id="appContainer"></div>
</body>

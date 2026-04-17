<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>3D Viewer</title>

  <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>
</head>

<body>
  <model-viewer
    src="./models/sample.glb"
    camera-controls
    auto-rotate
    autoplay
    style="width: 100%; height: 500px;">
  </model-viewer>
</body>
</html>

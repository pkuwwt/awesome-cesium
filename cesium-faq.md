
# Frequent Asked Questions about Cesium.js

## How to show frame rate (FPS)
```javascript
viewer.scene.debugShowFramePerSecond = false;
```

## How to close atmosphere
```javascript
viewer.scene.skyAtmosphere.show = false;
```

## How to create imagery layer
```javascript
var layer = viewer.imageryLayers.addImageryProvider(new Cesium.UrlTemplateImageryProvider({
    url: 'https://your-imagery-server/{z}/{x}/{y}.png',
}));
```

## How to remove the Cesium logo

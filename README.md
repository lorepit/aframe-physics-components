## aframe-physics-components

> Currently depends on aframe-core#dev

Physics components for [A-Frame](https://aframe.io) VR using [cannon.js](http://schteppe.github.io/cannon.js/).

### Usage

#### Browser Installation

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/latest/aframe.min.js"></script>
  <script src="https://github.com/ngokevin/aframe-physics-components/blob/master/dist/aframe-physics-component.min.js"></script>
</head>

<body>
  <a-scene>
    <a-entity physics-body="mass: 5"></a-entity>
  </a-scene>
</body>
```

#### NPM Installation

Install via NPM:

```bash
npm install aframe-physics-component
```

Then register and use.

```js
var AFRAME = require('aframe-core');
var physicsComponent = require('aframe-physics-components').physicsBodyComponent;
AFRAME.registerComponent('physics-body', physicsBody);
```

| Property | Description | Default Value |
| -------- | ----------- | ------------- |
|          |             |               |

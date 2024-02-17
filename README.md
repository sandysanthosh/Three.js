# Three.js

Three.js is an open-source JavaScript library that you can use to create dynamic and interactive websites with **2D and 3D graphics**. With Three.js, you can render **3D graphics** directly inside the browser. You can do fantastic stuff using Three.js by adding animations or logic and even turning your website into a game. Ricardo Cabello (or mrdoob in GitHub) released Three.js in 2010 and maintained a great open-source community.

Three.js is an open-source, lightweight, cross-browser, general-purpose JavaScript library. **Three.js** uses **WebGL** behind the scenes, so you can use it to render Graphics on an HTML <canvas> element in the browser. Since Three.js uses JavaScript, you can interact with other** web page elements**, add **animations** and **interactions**, and even create a **game with some logic**

### Why use Three.js?

        The following features make Three.js an excellent library to use.
        
        You can create complex **3D graphics **by just using JavaScript.
        
        You can create **Virtual Reality (VR)** and **Augmented Reality (AR)** scenes inside the browser.
        
        Since it uses WebGL, it has cross-browser support. Many browsers support it.
        
        You can add various materials, textures and animate 3D objects.
        
        You can also load and work on objects from other 3D modeling software.


### Three.min.js:

<script src='/path/to/threejs.min.js'></script>

### NPM:

npm install three

### Js class:

import * as THREE from 'three'



### Virtual Reality (VR) content to an HTML page, you can use the WebVR API or the newer WebXR API, depending on browser support and your specific requirements. Here's a basic example of how to add VR content using the WebVR API::

```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VR Example</title>
    <script src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
</head>
<body>
    <a-scene>
        <!-- Add VR content here -->
        <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
        <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
        <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
        <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
    </a-scene>
</body>
</html>

```





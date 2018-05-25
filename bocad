<html>
 <head>
  <title>Aveva Bocad model</title>
  <script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
   <script src="https://cdn.rawgit.com/tizzle/aframe-orbit-controls-component/v0.1.14/dist/aframe-orbit-controls-component.min.js"></script>
   </head>
 <body style=’margin : 0px; overflow: hidden;’>
   <a-scene>    

      <a-entity
          id="camera"
          camera="fov: 80; zoom: 1;"
          position="0 2 5"
          orbit-controls="
              autoRotate: false;
              target: #target;
              enableDamping: true;
              dampingFactor: 0.125;
              rotateSpeed:0.25;
              minDistance:3;
              maxDistance:100;
              "
          mouse-cursor="">
      </a-entity>

      <a-entity id="target">
     <a-gltf-model src="url(xentrys.gltf)" position="-11.5 0 0" scale="0.001 0.001 0.001" rotation="-90 0 0" gltf-model="xentrys.gltf"></a-gltf-model>
      </a-entity>
      </a-scene>    
 </body>
</html>

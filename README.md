## Welcome to <div class="verticalbottom"><img src="https://user-images.githubusercontent.com/4315156/90423535-a5345380-e08a-11ea-8bfa-70af4fdbcb7e.png" alt="Dicemoot" width="125" height="50"  vertical-align="text-bottom"></div>

Dicemoot is a isometric board game simulation environment that aims to make playing a boardgame digitally easier. The core feature of DiceMoot is  allowing players to import 2D images as 3D tokens or a scalable gridded map the tokens can be placed upon. This allows creation of objects, environment or characters that look nice on the board but also allows easier creation of assets without specilized knowledge of 3D sculpting.

### Proposed Implementation

For ease of access for users of all types a web interface would serve well. Rendering the 3D model of the game board, character tokens and the like could be implemented via [threejs](https://threejs.org/). Examples such as [this one](https://threejs.org/examples/#webgl_geometry_spline_editor) show most of the features necessary to implement the game with this library.

A proof of concept is necessary to show multiplayer access capability on a 3D board with multiple users connecting from different networks.

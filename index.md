## MRPT Web Framework
My Work briefly
* Implemented a C++ websocket server and a RPC handler capable of publish/subscribe mechanism.
  The link to the C++ library [mrpt-web](https://github.com/rachit173/mrpt-web).
* Created a client side JavaScript Library for handling the websocket communication. Also provides 2d, 3d visualisation modules
and laid the structure of library for future development of modules.

#### Link to Codes
* MRPT-web (C++ library) -> [main-repo](https://github.com/MRPT/mrpt-web),[my-repo](https://github.com/rachit173/mrpt-web)
* MRPT-web-js (JS library) -> [main-repo](https://github.com/MRPT/mrpt-web-js),[my-repo](https://github.com/rachit173/mrpt-web-js)
* rawlog-web-ui (app built on the framework)(https://github.com/MRPT/rawlog-web-ui),[my-repo](https://github.com/rachit173/rawlog-web-ui)
the main repos have been created from my repo

* MRPT (added schema based serialization abstract class): will add link to PR for serialization code here

#### Merge Status
All the repos have been merged completely with the organisation's repo,
* MRPT-WEB <br>
https://github.com/MRPT/mrpt-web
* MRPT-WEB-JS<br>
https://github.com/MRPT/mrpt-web-js
* Rawlog-Web-UI<br>
https://github.com/MRPT/rawlog-web-ui

#### What is done
* The RPC handling by websocket server in mrpt-web repo.
* Client side(JS) RPC handling using native websockets
* Client side(JS) 3d and 2d visualisation for poses, point clouds, paths, plots and other meshes based on three.js
* Created a functional app rawlog-web-ui with backend using the websocket server developed. The frontend developed using Vue.js and modules from mrpt-web-js. The web-gui based app allows users to visualize recorded [rawlogs](https://www.mrpt.org/Rawlog_Format).

#### Future development
The structure and core module have been implemented during the gsoc period. A lot of work can be done to extend functionality and simplicity of the library. Some of the work which would be direct extension to the current state is,
* MRPT-WEB
The stubs for RPC handling need to be created manually. A stub generator would enhance the user experience by reducing development time. Concrete examples showcasing publisher and subscriber over websockets would be useful additions.
* MRPT-WEB-JS
Transforms and messages module can be developed to provide completeness to the framework. Compatibility with ROS, and suitable apps or examples. 
* Rawlog-Web-UI 
Adding more features from the original [Rawlog Viewer](https://www.mrpt.org/list-of-mrpt-apps/rawlogviewer/)

##### Contact
rachittibrewal@gmail.com

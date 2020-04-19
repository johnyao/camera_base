^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package camera_base
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.3 (2020-04-19)
------------------
* Add time offset publisher
* add ros service to shutdown all camera driver nodes
* Merge pull request `#2 <https://github.com/johnyao/camera_base/issues/2>`_ from nicolov/master
  Install the header files
* Add install to CMakeLists
* add back CameraInfo message in Grab
* change default frame_id to cnh namespace
* remove CameraInfo from GrabImage
* remove unused dependency
* remove image_msg and cinfo_msg from class member
* add a launch file that launches image_proc and image_view
* fix not properly initializing diagnostic updater
* use pnh for private node handle
* Merge branch 'master' of https://github.com/KumarRobotics/camera_base
* add some comments
* Update README.md
* Revert "Merge pull request `#1 <https://github.com/johnyao/camera_base/issues/1>`_ from KumarRobotics/flippy"
  This reverts commit 42176e6250e089b4eeb616ea945968a7eced1baa, reversing
  changes made to db39258a2dd2a96826941ab090d28c189ce15f71.
* Merge pull request `#1 <https://github.com/johnyao/camera_base/issues/1>`_ from KumarRobotics/flippy
  added option to flip camera
* added option to flip camera
* get rid of the anonymous namespace in header file
* add namespace
* Update camera_node_base.h
  fix a typo
* change param camera to camera_name
* use private nodehandle to initialize reconfigure server
* put getParam in an anonymous namespace
* add a util function
* some apti change
* Merge branch 'master' of github.com:versatran01/camera_base
* add camerainfo to grab as well
* Update README.md
* Update README.md
* update
* Update README.md
* Update README.md
* Update README.md
* Update README.md
* Update README.md
* Update README.md
* Update README.md
* relax timestamp param to 0.1
* fall back to paren init
* update
* more brace init
* catkinize
* make image_msg and cinfo_msg have the same time
* use a camera namespace to resolve stereo camera name
* let image transport worry about publishing image_raw
* add a camera nodehandle for supporting stereo camera
* add accessor for fps
* add identifier
* update TimeStampStatusParam max acceptable
* update
* first commit
* Contributors: Chao Qu, John Yao, Mike Watterson, mwatterson, nicolov

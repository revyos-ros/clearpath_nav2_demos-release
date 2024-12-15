^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package clearpath_nav2_demos
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.0.0 (2024-11-25)
------------------
* Added minimum version.
* Add config files for dingo, ridgeback. Waiting for confirmation that the acceleration limits & max angular velocities are correct
* Copy velocity & acceleration limits from clearpath_control
* Contributors: Tony Baltovski, Chris Iverach-Brereton

0.2.0 (2024-01-22)
------------------
* Increased inflation radius
* Added W200 configs
* Contributors: Roni Kreinin

0.1.0 (2023-09-15)
------------------
* Updated get model function and remapped scan topics
  * Update get model function to match clearpath config
  * Remap to correct namespacing on scan topics
* Contributors: Hilary Luo

0.0.2 (2023-07-27)
------------------
* Updated sensor namespace
* Linter fix
* Contributors: Roni Kreinin

0.0.1 (2023-07-17)
------------------
* Added space to package.xml.
* Updated package.xml order.
* Added test dependencies.
* Added Github actions.
* Config updates
* Namespacing fixes
* Updated odom topics
* Fixed footprint and adjusted velocity/accel limits on J100
* Use config to set namespace and platform model
* Current best parameters for Husky
* Cleanup
* Jackal params
* Initial commit
* Initial commit
* Contributors: Hilary Luo, Roni Kreinin, Tony Baltovski

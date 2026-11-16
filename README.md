CAT workspace: VLP16 is retired by the 2026-11-12 decision Q2. This checkout
preserves upstream tag 2.5.1 (`0f2a3bb1dde4fa91cbafad8a3f9f89b66c2a1350`)
and its licenses/history for reference. `COLCON_IGNORE` removes the dedicated
driver from normal workspace discovery/build/install. Current CAT launch and
sensor selection do not use it. Recorded data and calibration history remain.

The following is the original upstream documentation, not the current CAT setup.

[![](https://github.com/ros-drivers/velodyne/workflows/Basic%20Build%20Workflow/badge.svg?branch=ros2)](https://github.com/ros-drivers/velodyne/actions)

Overview
========

Velodyne<sup>1</sup> is a collection of ROS<sup>2</sup> packages supporting `Velodyne high
definition 3D LIDARs`<sup>3</sup>.

**Warning**:

  The `<ros_distro>-devel` branch normally contains code being tested for the next
  ROS release.  It will not always work with every previous release.
  To check out the source for the most recent release, check out the
  tag `ros2-<version>` with the highest version number.

The current ``dashing-devel`` branch works with ROS Dashing.

- <sup>1</sup>Velodyne: http://www.ros.org/wiki/velodyne
- <sup>2</sup>ROS: http://www.ros.org
- <sup>3</sup>`Velodyne high definition 3D LIDARs`: http://www.velodynelidar.com/lidar/lidar.aspx

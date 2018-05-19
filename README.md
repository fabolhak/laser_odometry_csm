A [laser_odometry](https://github.com/artivis/laser_odometry) wrapper for csm.
---

[![Build Status](https://travis-ci.org/artivis/laser_odometry_csm.svg?branch=master)](https://travis-ci.org/artivis/laser_odometry_csm)

| Indigo            | Jade              | kinetic            |
|-------------------|-------------------|--------------------|
| [![Indigo][1]][1] | [![Jade][2]][5]   | [![kinetic][3]][5] |

[1]: https://travis-matrix-badges.herokuapp.com/repos/artivis/laser_odometry_csm/branches/master/1
[2]: https://travis-matrix-badges.herokuapp.com/repos/artivis/laser_odometry_csm/branches/master/3
[3]: https://travis-matrix-badges.herokuapp.com/repos/artivis/laser_odometry_csm/branches/master/5
[5]: https://travis-ci.org/artivis/laser_odometry_csm

The laser_odometry_csm package is a wrapper (a plugin) to use the [C(canonical) Scan Matcher (csm)](https://github.com/clearpathrobotics/csm/tree/catkinize_csm_eigen) in the [laser_odometry](https://github.com/artivis/laser_odometry) package.

Important: Do not install the default csm package via `sudo apt install ros-<distro>-csm`! Rather install csm from source using the [eigen version](https://github.com/clearpathrobotics/csm/tree/catkinize_csm_eigen) instead of the default GSL version.
This is a workaround to avoid a singular matrix [bug](https://github.com/AndreaCensi/csm/issues/24).

# Changelog

## [2021-10-20 - Version 1.0.2](https://github.com/microsoft/scenepic/releases/tag/v1.0.2)
Point release adding additional wheels to support Apple Silicon and some
minor UI changes.

Improvements:
- The dropdown menu visibility can be directly controlled via `UIParameters`
- A `standalone` parameter has been added to `save_as_script` to enable the
  creation of standalone scripts.

Bug Fixes:
- While transparent backgrounds were supported by the library, it was
  not exposed via the client APIs. This has been fixed via a 4D color parameter
  for `Shading`.

## [2021-10-7 - Version 1.0.1](https://github.com/microsoft/scenepic/releases/tag/v1.0.1)
Point release addressing various items that did not make the release. There will
not be a binary release as part of this change.

Improvements:
- Added new `hello_scenepic.py` and `hello_scenepic.cpp` example code
- Renamed `cppsrc` to `src`
- Added a clang-format pipeline and build targets
- Normalized C++ file format

Bug Fixes:
- `load_obj` now correctly loads normals when present in the OBJ file
- `MeshInfo` now exposes normals
- C++ build typos now fixed
- Fixed erroneous pipeline triggers


## [2021-10-4 - Version 1.0.0](https://github.com/microsoft/scenepic/releases/tag/v1.0.0)
Initial Release
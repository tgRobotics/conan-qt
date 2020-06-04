# Changelog

This changelog describes interface changes (options and requirements) in the conan package. For qt's changelogs, please go to https://wiki.qt.io/Template:Release_Information

## Unreleased
- migrate to `fontconfig/2.13.91` - 2020-06-04
## [5.15.0](https://bintray.com/bincrafters/public-conan/qt%3Abincrafters/5.15.0%3Astable)
- migrate to build requirement `flex/2.6.4` - [2020-05-21](https://github.com/bincrafters/conan-qt/commit/750851425c3f4217365f5a9aaa9d856e6533fdfd#diff-2b1d42f71f22b7ea0412d7602dec166f)
## [5.14.2](https://bintray.com/bincrafters/public-conan/qt%3Abincrafters/5.14.2%3Astable)
- upgrade to `openssl/1.1.1g` - [2020-05-06](https://github.com/bincrafters/conan-qt/commit/44c706a3a061f8dabe52eead5ee4d54417b4e863)
- upgrade to build requirement `bison/3.5.3` - [2020-04-28](https://github.com/bincrafters/conan-qt/commit/924d23fa77f54c9751c2345f2f01e939dd3dc856)
- add `with_vulkan` option - [2020-04-25](https://github.com/bincrafters/conan-qt/commit/448470871b2d9523a47937eae66621f01f161a1e)
- remove `with_mesa` option and `mesa` requirement. `opengl/virtual@bincrafters/stable` is required instead - [2020-04-13](https://github.com/bincrafters/conan-qt/commit/36f7702b142244cd503e12891d8bc7ac5d37504e)
- upgrade to `openssl/1.1.1g` - [2020-04-09](https://github.com/bincrafters/conan-qt/commit/5c04b3aac2bed31c5422da93db06a07a92cb2844)
- migrate to build requirement `gperf/3.1` - [2020-03-16](https://github.com/bincrafters/conan-qt/commit/229f375d3c5676ab1616ea6ec5ddd75ae8679a6f)
## [5.14.1](https://bintray.com/bincrafters/public-conan/qt%3Abincrafters/5.14.1%3Astable)
- add `with_mesa` option to allow disabling mesa requirement - [2020-03-11](https://github.com/bincrafters/conan-qt/commit/7c2f5bf147a609fb3ecd40549b3de30c21e63d41)
- upgrade to `harfbuzz/2.6.4@bincrafters/stable` - [2020-03-03](https://github.com/bincrafters/conan-qt/commit/39492329fb95ac2e2e1b9a9b37cfc5f74ef4f81c)
- upgrade to `sqlite/3.31.0` - [2020-03-03](https://github.com/bincrafters/conan-qt/commit/39492329fb95ac2e2e1b9a9b37cfc5f74ef4f81c)
- upgrade to `sdl2/2.0.10@bincrafters/stable` - [2020-03-03](https://github.com/bincrafters/conan-qt/commit/39492329fb95ac2e2e1b9a9b37cfc5f74ef4f81c)
- upgrade to `xkbcommon/0.10.0@bincrafters/stable` - [2020-03-03](https://github.com/bincrafters/conan-qt/commit/39492329fb95ac2e2e1b9a9b37cfc5f74ef4f81c)
- upgrade to `zstd/1.4.4` - [2020-03-03](https://github.com/bincrafters/conan-qt/commit/39492329fb95ac2e2e1b9a9b37cfc5f74ef4f81c)
- upgrade to `glib/2.64.0@bincrafters/stable` - [2020-02-28](https://github.com/bincrafters/conan-qt/commit/2a4167dc1a0a008f3570c7b3ff7c48ca5c6bf30f)
- upgrade to `glib/2.63.6@bincrafters/stable` - [2020-02-26](https://github.com/bincrafters/conan-qt/commit/10c0e0622dac3b5312670c236e6bc54ac682579e)
- upgrade to `libjpeg/9d` - [2020-02-01](https://github.com/bincrafters/conan-qt/commit/a5585a998f863d57a5601b2ab620ba9f8ef06641)
- upgrade to `libfreetype/2.10.1` - [2020-01-27](https://github.com/bincrafters/conan-qt/commit/25b2d262bfbe26a6df45d6edf60e29ab180f59d8)
- migrate to `opus/1.3.1` - [2020-01-22](https://github.com/bincrafters/conan-qt/commit/adff8c0c6e595102561c472f62b4d14f3a99bffc)
- upgrade to build requrement `jom/1.1.3` - [2020-01-13](https://github.com/bincrafters/conan-qt/commit/84168c7db987bdd9b3deeb497f2605bf146d4b65)
- remove system requirement on mesa. `mesa/19.3.1@bincrafters/stable` is required instead - [2020-01-09](https://github.com/bincrafters/conan-qt/commit/c6d8131be32e2b5fd10b509ea6ff574ed89f4b93)
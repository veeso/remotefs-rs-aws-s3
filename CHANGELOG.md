# Changelog

- [Changelog](#changelog)
  - [0.2.0](#020)
  - [0.1.0](#010)

---

## 0.2.0

Released on 05/02/2022

- Added support for S3 compatible APIs (such as minio, yandex)
- New constructor methods
  - `new()` will now accept only the bucket name
  - `region()` to specify the region. If no region is specified, custom region will be used
  - `endpoint()` to specify the endpoint. Useful to connect to minio
  - `new_path_style()`: must be specified when connecting to some backends, such as minio

## 0.1.0

Released on 04/01/2022

- First release

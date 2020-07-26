# Graylog Docker Image

Based on official Graylog repo: https://github.com/Graylog2/graylog-docker

## License

This Docker image is licensed under the Apache 2.0 license, see [LICENSE](LICENSE).

Graylog itself is licensed under the GNU Public License 3.0, see [license information](https://github.com/Graylog2/graylog2-server/blob/master/COPYING).

**NOTE: this build was modified by nicgrobler to change the UID / GID of the "graylog" user, and also to remove the VOLUME from the base image - this allows changes to be made downstream to permissions as needed.**

# docker-nut

[![Project Maintenance](https://img.shields.io/maintenance/yes/2020.svg)](https://github.com/pedrolamas/docker-nut 'GitHub Repository')
[![License](https://img.shields.io/github/license/pedrolamas/docker-nut.svg)](https://github.com/pedrolamas/docker-nut/blob/master/LICENSE 'License')

[![CI](https://github.com/pedrolamas/docker-nut/workflows/CI/badge.svg)](https://github.com/pedrolamas/docker-nut/actions 'Build Status')

[![Twitter Follow](https://img.shields.io/twitter/follow/pedrolamas?style=social)](https://twitter.com/pedrolamas '@pedrolamas')

Simple Docker image with [NUT (Network UPS Tools)](https://networkupstools.org/)

## Usage

Image by default starts as nut server on port 5201:

```sh
docker run -it --rm -p 3493:3493 ei99070/docker-nut
```

## License

MIT

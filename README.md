## Modern The Lounge theme for Modern IRC

[![GitHub release](https://img.shields.io/github/tag/ronilaukkarinen/thelounge-theme-midnight.svg?style=flat-square)](https://github.com/ronilaukkarinen/thelounge-theme-midnight/releases) [![The Lounge](https://img.shields.io/badge/tested%20with%20thelounge-4.2.0-ff9e18.svg?style=flat-square)](https://github.com/thelounge/thelounge) <a href="https://yarn.pm/thelounge-theme-midnight"><img alt="npm version" src="https://img.shields.io/npm/v/thelounge-theme-midnight.svg?style=flat-square"></a> <a href="https://npm-stat.com/charts.html?package=thelounge-theme-midnight&from=2016-02-12"><img alt="Total downloads on npm" src="https://img.shields.io/npm/dt/thelounge-theme-midnight.svg?colorB=007dc7&style=flat-square"></a>

Aiming to be the **perfect** The Lounge theme out there.

## Requirements

- The Lounge 4.2.0

## Features

- Minimal UI
- Easy on the eyes
- Conversation layout, see [#2591](https://github.com/thelounge/thelounge/pull/2591#issuecomment-785429158)
<s>- Automatic theme that has both day/light and night/dark versions based on your operating system setting</s> Currently only possible [here](https://github.com/pulinairc/thelounge-themes/blob/3584d5ed5240cc4e5c322f6dd2fdd768e9e0131b/dist/auto-day-midnight.css)
- Fixed preview images with correct dimensions
- Fixed most of The Lounge style bugs
- The most readable modern fonts on Retina and 60hz mobile screens

| Desktop view  | Mobile conversation layout |
| ------------- | ------------- |
| <img src="https://i.imgur.com/fOVc5Gt.png" width="800px" height="auto"> | <img src="https://i.imgur.com/MjMWZkz.png" width="390px" height="auto"> |

## Installation

``` shell
thelounge install thelounge-theme-midnight
```

### Development

#### I want to change something!

Please fork this repository and make your changes.<br>
If the changes are good we might even accept pull requests.

#### I want a bigger font to mobile

See [Midnight-accessible](https://github.com/pulinairc/thelounge-themes/blob/3584d5ed5240cc4e5c322f6dd2fdd768e9e0131b/dist/midnight-accessible.css) or use Custom CSS feature.

## Development

1. `cd /path/to/thelounge-themes`
2. `npm install`
3. Start coding by running in separate Terminal: `code .` or just use any editor you wish
4. Run watchers:

``` bash
scss --watch src/midnight.scss:midnight.css --style compressed
```

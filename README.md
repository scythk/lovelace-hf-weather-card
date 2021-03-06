# 和风天气卡片
[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)
[![Stable](https://img.shields.io/github/v/release/scythk/lovelace-hf-weather-card)](https://github.com/scythk/lovelace-hf-weather-card/releases/latest)

### 更新日志 ###
- 2022-07-05
1. Splitted custom_component and lovelace card.
2. HACS compatibility.

- 2019-08-23
1. 增加一个新样式，降水概率以柱形图显示，优化图形、文字排版，将`hf_weather-card_new.js`改名后覆盖`hf_weather-card.js`即可使用。注意这个样式建议使用PC版chrome浏览器观看，在手机浏览器上横坐标过窄会导致图形位置有偏差（应该chart.js的锅）。

### 简介 ###
基于和风天气的lovelace天气卡片，主要功能：
- 支持生成多个天气Entity
- 天气数据统一存储
- 天气卡片增加空气质量、小时预报、生活建议、数据更新时间
- 天气卡片更多信息增加生活建议详细数据
- 天气卡片图表增加下雨概率
- 天气卡片使用动态图标

### 使用说明 ###
见[个人blog](https://ljr.im/articles/plugin-%C2%B7-change-lovelace-weather-card-based-on-windy/)

### 参考 ###
- [和风天气插件组][1]
- [lovelace-weather-card-chart][2]
- [weather-card][3]

[1]: https://bbs.hassbian.com/thread-3971-1-1.html "和风天气插件组(天气预报+生活提示+小时预报+空气质量)"
[2]: https://github.com/sgttrs/lovelace-weather-card-chart "lovelace-weather-card-chart"
[3]: https://github.com/bramkragten/custom-ui/tree/master/weather-card "weather-card"

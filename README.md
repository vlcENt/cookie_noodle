# cookie_noodle
A special dish
https://chat.tl/t-QbKZ7V6pIU


{
  "expected_update_period_in_days": "2",
  "url": "http://www.weather.com.cn/weather1d/101280601.shtml",
  "type": "html",
  "mode": "on_change",
  "extract": {
    "day": {
      "css": "#today .clearfix li[1] .wea",
      "value": "text()"
    },
    "day_temperature": {
      "css": "#today .clearfix li[1] .tem span",
      "value": "text()"
    },
    "day_wind": {
      "css": "#today .clearfix li[1] .win span",
      "value": "normalize-space(.)"
    },
    "night": {
      "css": "#today .clearfix li[2] .tem span",
      "value": "text()"
    },
    "night_temperature": {
      "css": "#today .clearfix li[2] .win span",
      "value": "normalize-space(.)"
    },
    "night_wind": {
      "css": "#today .clearfix li[2] .wea",
      "value": "text()"
    }
  }
}

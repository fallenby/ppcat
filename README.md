# ppcat
Bongo cat stream overlay for OBS.
Supports both mouse and tablet.

## config.json
The configuration file (generated on start-up) contains 5 options:
```json
{
  "resX": 1680,
  "resY": 1050,
  "mouse": false,
  "keyLeft": 90,
  "keyRight": 88
}
```
`resX` - your screen resolution width  
`resY` - your screen resolution height  
`mouse` - `true` uses mouse sprites, `false` uses tablet sprites  
`keyLeft` - your Left Click button in osu!. Z by default  
`keyRight` - your Right Click button in osu!. X by default  
Please use a tool such as http://keycode.info/ to find keycodes for your own keys.

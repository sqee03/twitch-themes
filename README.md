# twitch-themes
Streaming themes for OBS.


### How to generate CSS from SASS with command line
Navigate to theme folder and execute one of commands bellow:

Generate CSS from SASS:
`sass theme.scss ../css/theme.css --sourcemap=none`

Watcher for one file:
`sass --watch theme.scss:../css/theme.css --sourcemap=none`

Watcher for entire directory:
`sass --watch sass:css --sourcemap=none`
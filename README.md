# Chromecast-Openhab-Binding
Chromecast plugin for openhab

Command:<br>
\<ip\>:\<direction\>:\<command\><br>

This is really early.<br>
This commands bellow is kind of the only command that works.

Example:<br>
Number  Volume "Volume [%s]" { chromecast="192.168.1.3:=:volume" }<br>
String  Status "Status [%s]" { chromecast="192.168.1.3:=:status" }<br>
String  App "App [%s]" { chromecast="192.168.1.3:<:app" }

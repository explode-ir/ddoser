# ddoser
this script has been created by 🥀explode-ir🥀

# how to use
unziping => cd ddosmon => mkdir build && cd build => cmake .. => make

# use 
optional, I usually run this inside a screen session screen

 sudo ./build/ddoser configs/example.lua

# Configurations
You can find and edit these configuration for you needs inside configs/home.lua

interface = "eth0"global_traffic_threshold = 900000global_packets_threshold = 225000ip_traffic_threshold = 500000ip_packets_threshold = 125000notification_traffic_threshold = 20000notification_packets_threshold = 20000ipblock_retry_ticks = 536001000notification_command = "./scripts/notificate "%1%" "%2%" &"onblockip_command = "./scripts/ipblock block %1% &"onunblockip_command = "./scripts/ipblock unblock %1% &"network_uncompromise_ticks = 30onnetwork_compromise_command = "./scripts/networkcompromise compromised &"onnetwork_uncompromise_command = "./scripts/networkcompromise uncompromised &"log="logs/home.log"watchedips="configs/example_watchedips.xml"notificationsubject="DDOS Monitor on server1 notification"

# contact to us

explode-tm@telegmail.com

# telegram channel

https://t.me/explode_tm

# status

![explode-ir github stats](https://github-readme-stats.vercel.app/api?username=explode-ir&show_icons=true&theme=midnight-purple)

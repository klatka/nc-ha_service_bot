# nc-ha_service_bot
Custom bot for Nextcloud Talk to call endpoints in Home Assistant

## Usage
1. Create an automation with webhook trigger in Home Assistant (Make sure to have POST enabled) - you can use sample automation
2. Create config.yaml from sample.config.yaml and replace with your values
3. Run go server
4. Add Nextcloud Talk Bot with `occ talk:bot:install "Home Assistant" "your_secret" "http://<your_go_host>:8088/message"`

## Credits
https://github.com/nextcloud/welcome_bot

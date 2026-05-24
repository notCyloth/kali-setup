# Kali Logging Setup Script
This script will set up logging in the ~/logs folder. The logs will be for every terminal and save both commands and output. It will also update the prompt to include times the commands were run.
## Features to be added
- Autoconfigure terminal to be GreenOnBlack and 0 opacity
- Install Linux ligolo-agent in ~/common_bins/proxies
- JuicyPotatoNG, GodPotato etc.
- Install remmina
## Important Notes
- As the logs in ~/logs also save output - passwords displayed will be exposed in these logs.
- Logs older than 5 days are silently deleted to make sure there isn't bloat. If you want to ensure they are safe - move/copy them before then!

Terminal naming scheme examples: ctfname_vpn, ctfname_recon, etc

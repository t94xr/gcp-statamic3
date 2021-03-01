# gcp-statamic3
Installation Script for Statamic3 on GCP

When you create a VM instance, run this script - before updating, it creates a 3GB swapfile, sets it up, mounts it and then updates debian 10 repos and upgrades it.


 ```bash
 curl -fsSL http://raw.githubusercontent.com/t94xr/gcp-statamic3/main/basic_setup | sh
 ```
 

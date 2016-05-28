# Ansible Ubuntu Setup

This script will help automate the initial server set up for Ubuntu, as in this [DigitalOcean Tutorial](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-16-04)

## Why does this exist?

After setting up a fresh VPS running Ubuntu, for example, on DigitalOcean, there is a checklist of basic things to do before the server can be considered secure and usable.
This includes:

 - Creating a non-root user
 - Giving them sudo privileges
 - Disable password authentication
 - Setting up a firewall
 - Install crucial software e.g. `git`, `make`, `zsh`, etc.

After spinning up a server more than once, having to do all the above by hand gets tedious real quick.

This script removes the need for manual intervention and helps you automate the initial server setup, so your workflow becomes:

 - Create server
 - Run this setup script
 - Get productive immediately

### License
This is licensed under the MIT license. See LICENSE for the full license text.

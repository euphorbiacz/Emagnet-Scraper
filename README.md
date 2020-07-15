# EMAGNET SCRAPER - v1.0

## <p align="center">![Screenshot](https://repository-images.githubusercontent.com/165741206/f9087e00-397d-11ea-9cab-1aea419f9448)

| Current Version    | News                            | Tested On                          |
| :----------------- | :-------------------------------- | :----------------------------------|
| `1.0`              |  Run your own serer for emagnet      | Linux/MacOS/OpenWRT/Windows/Android                               |

### About: 

Emagnet Scraper is a monitor tool so we can grab all urls from scrape.pastebin.com/api_scrape.php and store all uploads on our own server and share to people

Setup your own server for emagnet and store both pastebin-api.txt (full api) && pastebin.txt (raw files)

### Getting Started

# Install apache2 and configure it after your needs, once done 
# - you just need to create a folder in /var/www/html/emagnet/pastebim
# - and from now you will have things stored like:
# -
# - Recent uploads stored as raw format:            /var/www/html/emagnet/pastebin/yyy-mm-dd/pastebin.txt 
# - Recent uploads will also be stored in json: :   /var/www/html/emagnet/pastebin/yyy-mm-dd/pastebin.txt
# -
# - For find your own urls or at emagnet server, you can do as below:
# - Print all urls:         curl -Lvs https://nr1.nu/emagnet/pastebin/yyy-mm-dd/pastebin.txt
# - Print all urls in json: curl -Lvs https://nr1.nu/emagnet/pastebin/yyy-mm-dd/pastebin-api.txt|jq

![Screenshot](...)

![Screenshot](...)
### System Requirements


- Bash     - Find more info about _bash_ [here](https://www.gnu.org/software/bash/)
- Wget     - Find more info about _wget_ [here](https://www.gnu.org/software/wget/)
- Curl     - Find more info about _curl_ [here](https://github.com/curl/curl)

### Wiki Sections:

- [About](https://github.com/wuseman/EMAGNET/wiki/ABOUT) - 
_How everything started._
- [Previews](https://github.com/wuseman/EMAGNET/wiki/PREVIEWS) - 
_Previews can be found here._
- [Configurations-&-Installation](https://github.com/wuseman/EMAGNET/wiki/Configurations-&-Installation) - 
_Get started with spotify brute forcing - How emagnet will work with your openvpn files._
- [Regex - Tips For Search](https://github.com/wuseman/EMAGNET/wiki/Searching-&-Regex) - How To Find your facebook credenticals, if it has been leaked._
- [Leaked Databases](https://github.com/wuseman/EMAGNET/wiki/Leaked-Databases) - Various Public Leaks

## Changelog

[Versions changelog](CHANGELOG.md).

## Authors: 

* **wuseman <wuseman@nr1.nu\>** 

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details

### Contact

  If you have problems, questions, ideas or suggestions please contact me on *_wuseman@nr1.nu_  - For faster contact visit freenode irc network or the webchat and type '/msg wuseman hi!' in the input bar and I will reply you ASAP I will see the message.
  
  Enter Freenodes network via your own client 'chat.freenode.com:+6697 or use their new web client [here](https://webchat.freenode.net/)


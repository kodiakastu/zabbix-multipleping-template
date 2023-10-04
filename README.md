# Zabbix: Multiple ping

This template allows you to ping multiple targets. The default macros are set to public DNS resolvers.

## ⚙️ Installation

1. Select a branch according to your Zabbix version and download the xml.
2. Import *zbx_multipleping_template.xml* to Zabbix (Configuration -> Templates -> Import)
3. Add the template *ICMP Multiple Ping* to your host and configure
4. Customize the macros to your needs!

## 🏷️ Features
- ✔️ Customise ping targets
- ✔️ Customise all parameters for Ping
- ✔️ All macros are set with the usual default value and description
- 🔶 No Linked template!

## 📣 Triggers
Items witch checks are enable by default. Those with Xs are disabled by default. You can customise your triggers to your needs per network interfaces.

From this template:
- ✅ Unavailable by ping
- ❎ High response time
- ❎ High ping loss

## Issues
None so far! Let me know if you found one!


## License
[MIT](https://choosealicense.com/licenses/mit/)


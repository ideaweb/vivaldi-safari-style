# Vivaldi userChrome.css Safari style (macOS only)

This theme will make Vivaldi more compliant with macOS.

<p align="center"><img alt="Vivaldi with NelliTab" src="https://raw.githubusercontent.com/ideaweb/vivaldi-safari-style/master/img/preview.png"/><br/><i>Vivaldi with macOS theme and <a href="https://nellitab.io">NelliTab</a> new tab extension</i></p>

## Requirements

* Vivaldi 2.10 or higher for macOS
* Tabs must be placed on top. Other locations disable the theme.

## Installing

* [Clone](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository) (recommended) or just download this repository 
* Look for **common.css** in your [Vivaldi app folder](https://forum.vivaldi.net/topic/10549/modding-vivaldi)
* Add the content of **./css/userChrome.css** located in this repository to found **common.css** (Please do not use @import rule and do not mix up with the none working scss/userChrome.scss file of this repository)
* Restart Vivaldi that changes can take effect
* Create an own theme with your preferred colors (e.g. background #c3c3c3, foreground #333333, highlight #006ed7 and accent #e9e9e9 for system light)

An easier way is just to run the install script in this repository:

```bash
cd /path/to/vivaldi-safari-style
. install.sh
```

## Updating

A Vivaldi release removes your changes in common.css and breaks this theme. Please just install the theme again by hand or by using the install script. 

I recommend to use tools like [LaunchControl](https://www.soma-zone.com/LaunchControl/) to create an own user agent which runs the install script e.g. every minute.

Do not forgot to update the theme as well if a release changes its own styles.

## Troubleshooting

Please check the list of [known issues](https://github.com/ideaweb/vivaldi-safari-style/issues) to see if it has been previously reported. Otherwise, please open a ticket [here](https://github.com/ideaweb/vivaldi-safari-style/issues). 

---

Safari and macOS are trademarks of Apple Inc., registered in the U.S. and other countries.



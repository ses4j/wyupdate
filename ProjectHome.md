<br />
# wyUpdate: the open source updater program for Windows #

wyUpdate is the open source updater that's included with [wyBuild](http://wyday.com/wybuild/). wyUpdate checks for updates, downloads any that are available, and safely updates your program. It handles in stride obstacles like Windows Vista's, Windows 7's, and Windows 8's User Account Control (UAC), limited-user problems, and many other subtleties.

<a href='http://www.youtube.com/watch?feature=player_embedded&v=zE9f_jfBi_8' target='_blank'><img src='http://img.youtube.com/vi/zE9f_jfBi_8/0.jpg' width='640' height=385 /></a>

<br />
## How to build patches and release to your users ##

To build updates you need [wyBuild](http://wyday.com/wybuild/) ([download wyBuild now - free 21-day trial](http://wyday.com/wybuild/downloading.php)). From wyBuild you can create tiny patches to the latest version of your software.

  * <strong><a href='https://wyday.com/wybuild/buy/'>Buy a license to wyBuild</a></strong> (for commercial software projects) <br />
  * <strong><a href='http://wyday.com/wybuild/buy/special-prices.php'>Get a free license to wyBuild</a></strong> (for open source software projects)

<br />
## wyUpdate Features ##

Some of the notable features of wyUpdate are:

  * Full automatic update support using the [open source AutomaticUpdater control](http://wyday.com/wybuild/help/automatic-updates/).
  * [Silent update checking](http://wyday.com/wybuild/help/silent-checking.php) can be used with all programs no matter the language (C, C++, Delphi, Java, etc.).
  * Works in both Standalone mode and Automatic Update mode - seamlessly integrating with your .NET application.
  * Show info about your update to your users.
  * Ability to **patch files** using VCDIFF delta-patch format
  * **Rollback updates** if an unrecoverable error occurs or if the user cancels the update
  * Intelligent handling of all user-permission related problems (including **UAC** on Vista, Windows 7, and Widnows 8)
  * Can add/change/delete keys and values from registry
  * Can [execute \*.cmd, \*.bat, \*.exe, and \*.msi files before and after updates](http://wyday.com/wybuild/help/executing-files.php)
  * Creates shortcuts to your program files
  * Customize the theme to fit your corporate branding
  * Fully supports downloading from https sites & https site using self-signed SSL sites typical on corporate intranets
  * Full multilingual support, including automatic detection of you user's language.
  * [Installs & Uninstalls COM dlls](http://wyday.com/wybuild/help/com-registration.php)
  * [Start and stop Windows Services](http://wyday.com/wybuild/help/services.php).

wyUpdate is written in C# and is licensed under the BSD License.

<br />
## Works with Windows 2000 - Windows 8 ##

wyUpdate supports Windows 2000, XP, Server 2003, Vista, Server 2008, Windows 7, Windows 2012, and Windows 8.

<br />
## Screenshots ##

### List changes included in the update ###

Tell your users what's new in with your product.

![https://wyupdate.googlecode.com/files/wyupdate.changes.png](https://wyupdate.googlecode.com/files/wyupdate.changes.png)


### Quickly install the update ###

wyUpdate quickly downloads your update and patches your application.

![https://wyupdate.googlecode.com/files/wyupdate.updating.png](https://wyupdate.googlecode.com/files/wyupdate.updating.png)


wyUpdate installing updates on Windows 7 (with full system integration)

![https://wyupdate.googlecode.com/files/wyUpdate-installing.win7.png](https://wyupdate.googlecode.com/files/wyUpdate-installing.win7.png)

### Updates completed successfully ###

![https://wyupdate.googlecode.com/files/wyupdate.updated.png](https://wyupdate.googlecode.com/files/wyupdate.updated.png)


### Rolling back corrupt or canceled updates ###

wyUpdate can also gracefully handle errors and roll back to the previously working version.

![https://wyupdate.googlecode.com/files/wyupdate.rollingback.png](https://wyupdate.googlecode.com/files/wyupdate.rollingback.png)
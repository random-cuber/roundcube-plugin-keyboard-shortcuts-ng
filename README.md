# Roundcube plugin - Keyboard Shortcuts NG

Plugin that enables keyboard shortcuts, and makes associations configurable
by Roundcube admin.

Supports _almost all_ possible keyboard shortcuts (any combination of alt, ctrl,
meta and shift keys), and all of character, number, punctuation, direction, F1-F12
keys with addition of backspace and delete key + ctrl+enter for send mail.



## Installation

Like any normal Roundcube plugin. Use composer.json.



## Configuration

See [config/defaults.inc.php](config/defaults.inc.php) for details.
Local overrides are done _in main Roundcube configuration file_.
Files in plugin/keyboard_shortcuts_ng/config/ are ignored.



## TODO

Details that need attention:
- when previewpane is empty, 'c' for compose shortcut does not work - 404 because of skins/theme/... src= value
- fix help output to display actual associations
- add OS-native shortcuts (different for Mac OS X for example) - if adding them will suffice, excellent. Otherwise refactoring will be needed.



## Legacy

This plugin came to life as an offspring of original
[keyboard_shortcuts](https://github.com/corbosman/keyboard_shortcuts) plugin,
joined by a series of merges of almost all unmerged changes throughout GitHub,
fueled by major refactoring and implementation of configurable key associations.



## License

This plugin is distributed under the GNU Affero General Public License Version 3.
Please read through the file LICENSE for more information about this license.

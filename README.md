# giada-midimaps

This is the official repository of [Giada](http://www.giadamusic.com) **midimap files**. A midimap is a plain text file where you define **MIDI lightning messages**, special codes used to light up parts of external MIDI devices such as buttons, keys, knobs and many other shimmering things.

Midimap files reside in your configuration directory, or more precisely:

* Linux — `/home/[your_user]/.giada/midimaps/`;
* OS X — `[your_home]/Library/Application Support/Giada/midimaps/`;
* Windows — `midimaps/` folder, alongside the binary file.

## How to install a midimap file

Download the zip archive and uncompress it in the midimap folders seen before. Giada will look into those directories on startup. If the files are valid midimap files they will be listed in the Configuration window, MIDI section. 

For more information, please refer to the [official documentation](http://giadamusic.com/documentation/show/midi-output-management).

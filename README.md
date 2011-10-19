# Gedit3 plugins

* copy all of the files to `~/.local/share/gedit/plugins/` folder    


    `sudo cp org.gnome.gedit.plugins.restoretabs.gschema.xml /usr/share/glib-2.0/schemas/`    
    `sudo glib-compile-schemas /usr/share/glib-2.0/schemas/`

## Plugins included
* tabswitch
* pair char completion (thanks to [pair char autocomplete ](http://code.google.com/p/gedit-pair-char-autocomplete/source/browse/?name=gnome3))
* snapopen (thanks to [MadsBuus](https://github.com/MadsBuus/gedit-snapopen-plugin))
* whitespace remover (thanks to [Kozea](https://github.com/Kozea/Gedit-WhiteSpace-Terminator))
* restore tabs (thanks to [Quixotix](https://github.com/Quixotix/gedit-restore-tabs))
* smarthighlight

I have only tested them with ubuntu 11.10 (gtk3, gnome3)

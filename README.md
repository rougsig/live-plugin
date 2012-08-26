This is IntelliJ IDEA plugin for writing simple plugins in Groovy (or running Groovy code inside IntelliJ).

How to use:
 - open "Plugins" tool window on the right side
 - open and edit one of "plugin.groovy" files (these are entry points for plugins)
 - use "ctrl + C, ctrl + E" to execute current plugin

Plugins are stored on application level.
(Note that IDE support for editing plugins is very limited.)

To get full IDE support it can be useful to set up a project with all plugins and IntelliJ JDK attached.
You can set up a project for all plugins at the following folder:
 - $HOME/.$INTELLIJ_VERSION/config/intellij-eval-plugins/
 - (on Mac) $HOME/Library/Application Support/IntelliJIdea12/intellij-eval-plugins/


Why:
 - useful for simple or throw-away plugins
 - make plugins easy to change
 - plugins with immediately available source code
 - it's a good way to quickly try IntelliJ API


The idea of running code inside IntelliJ is not original. There are similar plugins:
- http://plugins.intellij.net/plugin?pr=idea&pluginId=3674
- http://plugins.intellij.net/plugin?pr=idea&pluginId=4660
- http://plugins.intellij.net/plugin/?id=5373
- http://plugins.intellij.net/plugin?pr=idea&pluginId=1020
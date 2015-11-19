# Introduction #

Use the following to get started with radial menu widget. Radial widget can be used over normal menus in android as it is visually more appealing and has a better UI experience.

# Features #

  * Fully customizable in terms of background color, text size and color, icon scaling, widget size and positioning on the screen.

  * Easy implementation.

# Usage #

To use radial menu in your andorid application, download the library file form the downloads page and place in the libs folder (create one if it doesnt exsists) of your project.

  * In your class file add make a new object of the radial menu widget and menu item.
> _RadialMenuWidget pieMenu;_
> _RadialMenuItem menuItem;_

  * Init the objects
> _pieMenu = new RadialMenuWidget(this);_
> _menuItem = new RadialMenuItem("Test","Test");_

  * Add it to the widget using
> _pieMenu.addMenuEntry(menuItem);_

  * Use _pieMenu.show(v);_ to display the menu and _pieMenu.dismiss();_ to remove menu.

**Note:** The widget will automatillay remove itself if toch is detected outside of the drawing area.
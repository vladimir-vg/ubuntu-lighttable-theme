Ubuntu LightTable theme
=======================

This theme is not added to plugin index yet, so you need to install it manualy.
Simply clone this repo into your `deploy/plugins` directory.

    $ cd LightTable/deploy/plugins
    $ git clone https://github.com/vladimir-vg/ubuntu-lighttable-theme.git

When it's done you have to set it as a current theme in your user behaviors file.
Open `Commands` view, then `Settings: User behaviors`. Add behavior to editor object:

    :editor [(:lt.objs.style/set-theme "ubuntu")]

You're done! Now you probably need to restart LT.

# Examples

# ClojureScript

![ClojureScript](http://s27.postimg.org/wvkoajkxv/cljs.png)

# Ruby

![Ruby](http://s27.postimg.org/bjd6cv0zn/ruby.png)

# CoffeeScript

![CoffeeScript](http://s27.postimg.org/pr2v1idoj/coffeescript.png)

# C

![C Language](http://s27.postimg.org/cph6bnpab/image.png)

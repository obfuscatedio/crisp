# Crisp-obfuscatedio

A minimalist, responsive, and open-source two-column theme for the [Ghost](http://ghost.org) publishing platform by originally created by [Kathy Qian](http://kathyqian.com), modified and updated by [Ryan Roy](https://www.obfuscated.io). Last tested with Ghost v3.4.0.

![Desktop Screenshot](https://raw.github.com/obfuscatedio/crisp/master/assets/screenshot-desktop.png)   

### Required Steps for Installation

1. Download the files   
2. Configure the follow buttons in **partials/follow.hbs** (see section below)
3. Zip the files, upload through the Ghost admin panel, and activate

### Suggested Customizations

* Change the link color on *line 88* in **assets/styles/crisp.css**
* Add code for Google Analytics in **default.hbs** after `{{ghost_foot}}`
* Replace the Disqus universal embed code in **partials/comments.hbs**, or delete the #comments div to remove comments altogether
* Remove irrelevant social sharing services in **partials/share.hbs**, or change the colors of social sharing services in **assets/styles/rrssb.css**
* Change your blog logo to change the favicon and cover photo to change the sidebar background

### Editing Follow Buttons

Crisp uses Font Awesome for icons. See the Font Awesome documentation for the [full list of icons](http://fortawesome.github.io/Font-Awesome/icons/) and [usage tips](http://fortawesome.github.io/Font-Awesome/examples/).

I have placed some common buttons in **follow.hbs**, with more options in the commented out sections. Make sure to replace the `username` in the URLs so the links point to your profiles.

### Features, Changelog, and Technical Notes

Below is a summary of updates since the initial release. If you need more detail, I suggest reading the [full commit history](https://github.com/obfuscated.io/crisp/commits/master/). For an idea of the roadmap and open issues, please refer to the [current open issues](https://github.com/obfuscatedio/crisp/issues?state=open).

This is being updated and maintained to work with most modern browsers, compatibility is the users responsibility.

**Version 1.0.0 &mdash; February 2, 2020**

* Updated for compatibility with Ghost v3.4.0

### Credits

Original creator and maintainer [Kathy Qian](http://kathyqian.com).

Many thanks to [@davegandy](http://twitter.com/davegandy) for the [Font Awesome](https://github.com/FortAwesome/Font-Awesome) icons used throughout the theme.

Social sharing buttons are a modified version of the [Ridiculously Responsive Social Sharing Buttons](https://github.com/kni-labs/rrssb) by [@dbox](http://www.twitter.com/dbox) and [@seagoat](http://www.twitter.com/seagoat).

### License

This theme is licensed under the [MIT License](https://github.com/obfuscatedio/crisp/blob/master/license.txt). Please keep the footer links in tact!

### More Screenshots

![Single Post Screenshot](https://raw.github.com/obfuscatedio/crisp/master/assets/screenshot-single.png)

![Mobile Screenshot](https://raw.github.com/obfuscatedio/crisp/master/assets/screenshot-mobile.png)

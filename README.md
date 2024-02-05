OVERVIEW
--------
This directory contains win3x-gtk-theme, a GTK2/3 theme which
emulates the Windows 3.x look and feel.  Color scheme is from
the Windows 3.1 theme called "Arizona".

This distribution was initial a fork of matthewmx86's "Win3xE Win95" theme,
adjusted to dark cyan colorscheme, with small GTK3 fix:
light tooltip background makes it unreadable on Java apps.
Later was added Win3x-Sol, the mix of "Win3xE Seven" and "Win3x ThreeZero"
themes.  Also was added Fluxbox-Win3x (style for Fluxbox window manager),
the hardly modified version of nicepics13's win311 theme.

See git log for further differences.

The original sources can be downloaded from:
1. https://www.pling.com/p/1309837/ (GPLv3+, used there)
2. https://github.com/matthewmx86/Win3xE (BSD-2-Clause version found on GH)
3. https://www.box-look.org/p/1571083


PREVIEW
-------
**Fluxbox-Win3x**:

![](screenshots/Fluxbox-Win3x.png)

**Win3x-Sol**:

![](screenshots/Win3x-Sol.png)

**Win3x-Win95-Cyan**:

![](screenshots/Win3x-Win95-Cyan.png)


REQUIREMENTS
------------
GTK2 theme requires Redmond(95) engine from gtk-engines package.


NOTES
-----
For Qt5 apps to match the theme you can install `qt5ct` and `qt5-styleplugins`
and the select gtk2 theme in qt5ct.  Make sure to set the environment variable
`QT_QPA_PLATFORM_THEME=qt5ct` for Qt5 apps to use the theme.

To disable GTK3 apps from hiding unfocused scrollbars, set the environment
variable `GTK_OVERLAY_SCROLLING` to `0`.


KNOWN ISSUES
------------
**by matthewmx86**:
```
There are some issues with this theme and LibreOffice.
Right now it's kind of a disaster so I recommend to use the
environment variable SAL_USE_VCLPLUGIN="gtk" in the meantime
until I can fix the issues.
```


LICENSE
-------
win3x-gtk-theme is licensed the same as obtained `Win3xE Classic`,
through GNU General Public License v3 or later
<https://gnu.org/licenses/gpl.html>.
Read the COPYING file for copying conditions.
Read the COPYRIGHT file for copyright notices.

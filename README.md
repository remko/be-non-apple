# [Belgian (Non-Apple) Keyboard Layout](http://el-tramo.be/software/be-non-apple)

## About

This is a Mac OS X keyboard layout for 'standard' Belgian
The international keyboard layout (as opposed to the Apple-specific one)
The main difference is that signs such as @ and # are accessed using AltGr.


## Installation

- Place the `Belgian (Non-Apple).keylayout` file in `/Library/Keyboard Layouts`
  or `/Users/<username>/Library/Keyboard Layouts` 
- Log out and back in
- From the *Input Menu* *International* preference pane, select 
	the layout called *Belgian (Non-Apple)*

Making it the default seems to be tricky: the keyboard sometimes seems to
jump back to the default layout. Disabling the default keyboard seems 
impossible since the checkbox is greyed out and unaccessible. I still 
haven't found how to solve this, so I just move the whole `Roman.bundle`
out of the System library and put it where Mac OS can't find it.

## TODO

- Make some kind of icon for it, preferably different than the default Belgian flag from Mac OS X.

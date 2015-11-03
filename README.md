# PIF Editor
HTML5 canvas-based synchronizing multi-device editor for editing different
pixeldata formats (such as [`pif`](//github.com/flaki/pif/) ), and creating
monochrome pixelart for embedded devices's displays, such as the [Arduboy](//github.com/arduboy/arduboy) Arduino-based gaming device and others.

## What is a PIF?
PIF is short for `P`ixeldata `I`mage `F`ormat, a plain-text-based intermediary
format to facilitate the creation and sharing of low-resolution, monochrome
image data.

These images are most frequently used in tiny, DIY LCD/LED/OLED displays in
conjunction with small embedded hardware. Creating such images should be
straightforward, but is hindered by the missing simple tooling and the
output requirement of a non-trivial binary pixelformat.

This editor uses the [`pif`](//github.com/flaki/pif/) library for reading
files, converting between different representations and working with the
PIF format.

## What is this PIF editor (good for)?
This editor tries to address three basic problems with the creation of
monochrome bitmaps:
 - **Accessibility:** written in pure HTML5 with web technologies, usable on practically all platforms, from desktop to mobile.
 - **Ergonomy:** due to the syncing nature, using the best tool for the job becomes possible: draw on touch device (mobile, tablet), copy the code on desktop, paste, compile & push it on the device for displaying.
 - **Shareability:** PIF files are simple text files, one could edit them by hand and share across projects with relative ease. They are also simple enough to be self-explanatory so (compared to proprietary, binary formats) third party tools could easily be created to use them.

## How to use?

## Changelog
- 0.1.1 (2015.05.03) Additional file type support
  - support for loading BMP bitmaps (1bit,24bit,32bit) as per [paulbourke](http://paulbourke.net/dataformats/bmp/)
  - support for subfolders on the server-side for `/sprites/`
  - support for multiple file extensions for `/sprites/` folder
  - added BMP testfiles via [Begemmed](http://www.team-arg.org/BGEM-downloads.html) by `team-arg`
- 0.1.0 (2015.05.02) Initial release

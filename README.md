# Kollage
<img src="https://i.8upload.com/image/2f572997922b29b4/logo-kollage-1200.png" width="200">

Kollage is a lightweight browser-based image editing application built with HTML, CSS and JavaScript. It was created to address a personal need: being able to work with `.pdn` files on Linux while enjoying an interface and workflow as close as possible to [Paint.NET](https://www.getpaint.net/).

The goal was never to reinvent image editing or compete with established software. I simply wanted a tool that suited my own needs and made creating and editing images more comfortable on my operating system of choice.

I'm sharing Kollage publicly in the hope that other people might find it useful too.

## Features

Kollage includes a range of tools for everyday image editing and photomontage:

- **Drawing tools:** Paintbrush, pencil, eraser, lines, geometric shapes, gradients, and text.
- **Tablet and stylus support:** Pointer-based input for mouse, touch, and pen, including pressure-sensitive brush width, an optional stroke stabilizer, pinch-to-zoom, and two-finger panning.
- **Selections:** Rectangular and elliptical selections, freehand lasso, magic wand, additive selections, and pixel manipulation.
- **Layer management:** Create, duplicate, reorder, merge, and manage layers, including visibility, opacity, and blending modes.
- **Image adjustments and effects:** Brightness, contrast, hue, saturation, black and white, sepia, blur, sharpening, pixelation, noise reduction, and other visual effects.
- **Editing history:** Undo and redo, with history limited to 60 states to reduce memory usage.
- **Image transformations:** Crop, resize, flip, and rotate images.
- **Color tools:** A redesigned color window with a hue and saturation wheel, RGB and HSV sliders, alpha controls, hexadecimal color input, a palette, and a color picker.
- **Import and export:** Open common image formats, work with `.pdn` files, import GIF frames as layers, import SVG images as raster layers, and read and write `.kra` files. Projects can also be saved in Kollage's own `.kol` format.
- **Workspace customization:** Zoom controls, multiple document tabs, movable panels with window snapping, and a pixel grid at high zoom levels.
- **Interface customization:** Dark theme and interface translations for English, French, Spanish, German, and Japanese.
- **Text customization:** Font selection, font size, bold and italic styling, with support for importing fonts.

Kollage is built with standard web technologies and runs in a compatible browser. It is also designed so it can potentially be packaged as a desktop application.

## Current Status

Kollage is usable, and version **1.3.1** adds improvements to drawing tools, selections, tablet support, the interface, file compatibility, and performance.

However, Kollage is still a personal project rather than a fully polished, professionally maintained image editor. Some features may behave unexpectedly, and bugs or compatibility issues are possible.

Known limitations include:

- **Rotations and transformations:** Some operations may still produce unexpected results. Undoing the last action with `Ctrl+Z` may help recover from an issue.
- **Pixel art:** Pixel-perfect mode and the image pixel grid are available, but Kollage is not specifically optimized for professional pixel-art workflows.
- **Extension system:** The extension system is not currently functional. Support for extensions is planned to make it easier to add effects without modifying the original source code.
- **Translations:** The interface supports English, French, Spanish, German, and Japanese. Some text, buttons, or dialogs may still fall back to English.
- **KRA compatibility:** Kollage can read and write `.kra` files, but compatibility with Krita has not been fully verified. Reading has limitations: groups are flattened, and vector layers, clone layers, masks, and unsupported color spaces may not be preserved. Files saved by Kollage are written as 8-bit RGBA.
- **SVG import:** SVG files are rasterized at the requested width onto a white background. They are not preserved as editable vector graphics.
- **GIF import:** Importing all frames as layers requires a browser that supports `ImageDecoder`, such as a compatible version of Chrome.
- **Feature completeness:** Some tools and workflows still need further testing and refinement.
- **Saving on Android:** It is unfortunately currently unavailable to save files on Android.

Version 1.3.1 has been tested on an Android tablet, a Windows 11 laptop, and a Fedora desktop. These tests do not guarantee compatibility with every device, browser, operating system, or file format.

Please keep backups of important projects and exported files.

## A Note About How Kollage Was Created

Kollage was developed through **vibe coding**, with AI assistance, because I had a specific problem I wanted to solve: editing `.pdn` files on Linux in an environment that felt familiar to me as a Paint.NET user.

I am not claiming to be the original author of every idea behind this kind of software, nor am I claiming any particular technical achievement. I used the tools available to me to build something that met my personal needs.

I also want to be transparent about the project's limitations. I cannot guarantee that Kollage is free of bugs, that every feature works as intended, or that it will be suitable for every use case. Use it at your own discretion, and keep backups of your work.

**My position on AI is neutral.** I am neither against it nor unconditionally in favor of it. I see it as a tool, and Kollage is one example of how I used it to address a practical problem.

As for the logo, I’m not the best at making them but i made it on my own on this tool, it’s meant to be a K with a G drawn over it using a brush (KollaGe) and yeah... I don't really know if it looks good but we have a logo!

## Let's be clear

I want to be clear about one thing: **Kollage started as a personal project, not as a commitment to maintain a fully featured image editor for everyone.**

I do not particularly focus on frequent updates or a strict release schedule. This version is intended to be close to a final version for my original needs, unless further changes become necessary. That does not mean the software is finished, it simply means that my personal requirements were the reason the project existed in the first place.

I am sharing it freely because someone else might have the same problem I had. If it helps another Linux user edit `.pdn` files or provides a familiar image-editing environment, then making it available is worthwhile.

I would be genuinely happy to see **actual developers and other interested people take over, fork, improve, or adapt Kollage** to suit their own needs. You are welcome to explore the code, report issues, suggest improvements, and build upon the project.

I do not expect the community to wait for me to implement every requested feature. If you need something that Kollage does not offer, feel free to experiment with the code or create your own version. I'll add the extension part so it's easier for you to add effects for Kollage without editing the source code (like paint.net)

## Feedback and Contributions

Despite the project's personal origins, constructive feedback is welcome.

If you encounter a bug or have an idea for an improvement, feel free to open an issue or submit a pull request.

Please understand that I may not respond to every request or actively maintain the project indefinitely. Forks, and community-led development are especially welcome.

## Final Words

Kollage is a personal tool that I decided to share, not a promise of a commercial-grade product or continuous development.

It may not be perfect, and it certainly has room to grow. But if it solves a problem for you or makes your workflow a little easier, then it has already served a useful purpose.

**Use it, experiment with it, improve it, fork it, and make it your own, because it does not belong to me.**

Thanks for taking a look at Kollage.

<p float="left">
  <img src="https://i.8upload.com/image/3add4419b423e0c4/screenshot-2026-10-22-13-50-31-164.jpg" width="500"/>
  <img src="https://i.8upload.com/image/5e9018114717afee/2026-10-22-14-12-02.png" width="500"/>
  <img src="https://i.8upload.com/image/6f5bb868da7fa873/capture-d-cran-20261022-110125.png" width="500"/>
  <img src="https://i.8upload.com/image/6cdef82dda272377/capture-d-cran-20261022-135328.png" width="500"/>

</p>

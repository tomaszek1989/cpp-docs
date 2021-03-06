---
title: "Choosing a Transparent or Opaque Background (Image Editor for Icons)"
ms.date: "11/19/2018"
helpviewer_keywords: ["opaque backgrounds [C++]", "colors [C++], image", "Image editor [C++], transparent or opague backgrounds", "images [C++], transparency", "images [C++], opaque background"]
ms.assetid: 61b743d9-c86b-405d-9a81-0806431b4363
---
# Choosing a Transparent or Opaque Background (Image Editor for Icons)

When you move or copy a selection from an image, any pixels in the selection that match the current background color are, by default, transparent; they do not obscure pixels in the target location.

You can switch from a transparent background (the default) to an opaque background, and back again. When you use a selection tool, the **Transparent Background** and **Opaque Background** options appear in the **Option** selector on the **Image Editor** toolbar (as seen below).

![Background options &#45; opaque or transparent](../windows/media/vcimageeditoropaqtranspback.gif "Background options &#45; opaque or transparent")<br/>
**Transparent and Opaque Options** on the **Image Editor Toolbar**

### To switch between a transparent and opaque background

1. In the **Image Editor** toolbar, click the **Option** selector, and then click the appropriate background:

   - `Opaque Background (O)`: Existing image is obscured by all parts of the selection.

   - `Transparent Background (T)`: Existing image shows through parts of the selection that match the current background color.

   \- or -

1. On the **Image** menu, select or clear **Draw Opaque**.

You can change the background color while a selection is already in effect to change which parts of the image are transparent.

For information on adding resources to managed projects, please see [Resources in Desktop Apps](/dotnet/framework/resources/index) in the *.NET Framework Developer's Guide*. For information on manually adding resource files to managed projects, accessing resources, displaying static resources, and assigning resource strings to properties, see [Creating Resource Files for Desktop Apps](/dotnet/framework/resources/creating-resource-files-for-desktop-apps). For information on globalization and localization of resources in managed apps, see [Globalizing and Localizing .NET Framework Applications](/dotnet/standard/globalization-localization/index).

## Requirements

None

## See Also

[Accelerator Keys](../windows/accelerator-keys-image-editor-for-icons.md)<br/>
[Working with Color](../windows/working-with-color-image-editor-for-icons.md)
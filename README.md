# Preload Resources - Atom for Gantry
This project contains a Gantry Atom that provides the functionality to manually define which static resources should be preloaded within the Gantry templating framework. **Preload Resource** encapsulates the parameterization of `link` tags to control the resource (pre-)loading behaviour. Furthermore, it provides an easy, user friendly and GUI assisted configuration and integration. In the current revision the following CMSs are supported:
* Joomla
* Wordpress
* Grav

## Prerequisites
* CMS (Joomla, Wordpress, Grav)
* Gantry Templating Framework and Theme - **at least v5.4.24**

## Download
Choose the correct download for your target platform. The Joomla Plugin System is supported for all Gantry themes globally or locally for the templates Helium and Hydrogen. The latest Atom version is **v1.0.0**.
___
**Default Atom:**
[English](https://github.com/thexmanxyz/Preload-Resources-Atom-Gantry/releases/download/v1.0.0/pra.atom.only.EN.v1.0.0.zip) / [German](https://github.com/thexmanxyz/Preload-Resources-Atom-Gantry/releases/download/v1.0.0/pra.atom.only.DE.v1.0.0.zip)

**Legacy Atom - Gantry <5.3.2:**
[English](https://github.com/thexmanxyz/Preload-Resources-Atom-Gantry/releases/download/v1.0.0/pra.atom.only.legacy.EN.v1.0.0.zip) / [German](https://github.com/thexmanxyz/Preload-Resources-Atom-Gantry/releases/download/v1.0.0/pra.atom.only.legacy.DE.v1.0.0.zip)

**Joomla Plugin - All Templates (Global):**
[English](https://github.com/thexmanxyz/Preload-Resources-Atom-Gantry/releases/download/v1.0.0/pra.j3.global.EN.v1.0.0.zip) / [German](https://github.com/thexmanxyz/Preload-Resources-Atom-Gantry/releases/download/v1.0.0/pra.j3.global.DE.v1.0.0.zip)

**Joomla Plugin - Hydrogen:**
[English](https://github.com/thexmanxyz/Preload-Resources-Atom-Gantry/releases/download/v1.0.0/pra.j3.hydrogen.EN.v1.0.0.zip) / [German](https://github.com/thexmanxyz/Preload-Resources-Atom-Gantry/releases/download/v1.0.0/pra.j3.hydrogen.DE.v1.0.0.zip)

**Joomla Plugin - Helium:**
[English](https://github.com/thexmanxyz/Preload-Resources-Atom-Gantry/releases/download/v1.0.0/pra.j3.helium.EN.v1.0.0.zip) / [German](https://github.com/thexmanxyz/Preload-Resources-Atom-Gantry/releases/download/v1.0.0/pra.j3.helium.DE.v1.0.0.zip)
___

## Automatic Installation (Joomla only)
1. Download the Plugin of the *Preload Resources Atom* for **Hydrogen, Helium or Global** installation.
2. Install it over the Joomla Plugin System.

*If you install the plugin globally be aware that the resource location changes to `/media/gantry5/engines/nucleus`*

## Manual Installation
1. Download the **Default Package** of the *Preload Resources Atom*.
2. Extract the files.
3. Copy the `.html.twig` and the `.yaml` file to your particle folder `/[GANTRY_THEME]/custom/particles`. Please check the [listing](https://github.com/thexmanxyz/Preload-Resources-Atom-Gantry#cms-template-folder) below to determine where the template folder for your CMS is located.

## CMS Template Folder
Please be aware that the template folder path varies in dependence of the used CMS. Here is a list of the folders for the different platforms:

### Wordpress
`/wp-content/themes/[GANTRY_THEME]`

### Joomla
`/templates/[GANTRY_THEME]`

### Grav
`/user/data/gantry5/themes/[GANTRY_THEME]`

## Configuration
1. Go to your Gantry templating backend (e.g. Extensions/Templates).
2. Switch to **Page Settings** and add the new appearing Atom called **Preload Resources** either globally to your site (**base outline**), to a specific template or page by dragging it to the designated section.
3. Configure the appearance according to your favor.

## Supported Parameters and Atom Options
* Supports multiple `link` tags for preloading of resources
* Selective deactivation of resources
* Options to define resource type and origin 

## Showroom
Insight of the *Preload Resources - Gantry Atom* configuration:

**Backend (1)** - *[General (a)](/screenshots/backend_general_a.png)*

![1](/screenshots/backend_general_a.png)


**Backend (2)** - *[General (b)](/screenshots/backend_general_b.png)*

![2](/screenshots/backend_general_b.png)

## Future Tasks
- [?] Currently no future tasks known.

## Known Issues
* None

## Dependencies
[Gantry Framework](http://gantry.org/)

## Credits
Thanks to the Gantry team for providing a modern templating framework.

## by [thex](https://github.com/thexmanxyz) | [gantryprojects](https://gantryprojects.com)
Copyright (c) 2019, free to use in personal and commercial software as per the [license](/LICENSE.md).

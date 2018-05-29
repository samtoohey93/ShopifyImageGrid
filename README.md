# ShopifyImageGrid
An Image Grid Usable in Timber Themes across the Shopify Platform. Please note this is not a dynamic section and requires to be added manually to an alternative page template in order o be used. It also cannot be re-positioned at this current time

USECASE
Creates a Flexbox based Image Grid (Can be used in a CSS Grid method as well on certain themes like Jumpstart or Brooklyn which have active Grids built into their Theme's SCSS

Import the SCSS file into the bottom of your Theme.scss.liquid file and create a new section (Preferably image-grid.liquid) with a .liquid file extension. 

Either add the section to an existing Page Template file, or create a new Alternative page template adding {{ include "your section name here" }} and presto!!


Current Limitations --> 
    Section requires theming alterations with the theme you are importing this to to customise it to the appropriate styling you are     working on

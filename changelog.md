# OceanWP Changelog

### *2017.02.15* - 1.1.5
* **Fixed** - Sub menus blinking.
* **Fixed** - Problem double lightbox with Beaver Builder.
* **Fixed** - Problem with WooCommerce images variation products.

### *2017.02.06* - 1.1.4
* **Added** - Register translation string.
* **Tweak** - All archive product éléments added în separate functions to easily alter them via thé child thème.
* **Fixed** - Excerpt issue with the Elementor WooStore plugin.
* **Deleted** - Modal scripts, integrated into the Ocean Modal Window extension.

### *2017.01.27* - 1.1.3
* **Added** - New panel in the customizer "Sidebar" to add background, control margin, padding, etc.
* **Added** - New lightbox script "Chocolat" in replacement of Magnific Popup, lighter, responsive, possibility to add the lightbox in full screen and zoom on the image, more info: http://chocolat.insipi.de/
* **Fixed** - Logo issue if youv've not set a retina logo, the custom logo not disappear anymore on retina screen.
* **Fixed** - Problem with the transparent header in the editor mode of Elementor.
* **Fixed** - Problem with images alignements.
* **Fixed** - Small issues.

### *2017.01.15* - 1.1.2
* **Added** - Script to create modal, check: http://docs.oceanwp.org/article/356-how-to-create-modal/
* **Added** - New functions for the new settings of the metabox.
* **Added** - Several hooks through the theme for the Ocean Hooks extension.
* **Added** - FitVids script to have responsive videos.
* **Added** - Filter for the style of the header, now you can alter the header style via the child theme.
* **Tweak** - Improvement of the local scrolling, now the height of the header is taken into account.
* **Fixed** - Problem of the retina logo on the retina screen.
* **Fixed** - Background color of the page header.
* **Fixed** - Small issues.
* **Deleted** - Responsive.css file, directly integrated into the style.css file.

### *2016.12.30* - 1.1.1.1
* **Added** - Category description on the shop page.
* **Fixed** - Non clickable products images with the gallery style.

### *2016.12.30* - 1.1.1
* **Added** - New awesome option to create your own header style.
* **Added** - Gallery lightbox for the default WordPress gallery.
* **Added** - Two new widgets Custom Header Logo and Custom Header Nav to use with your page builder for the Custom Header style.
* **Added** - Custom Menu widget with more options than the default WordPress widget.
* **Added** - Options to add an image background to the page header (title) for all your pages via the customizer.
* **Added** - New options in the Blog section of the customizer to add your featured images of your posts directly in the page header (title).
* **Added** - New option in the Blog section of the customizer to add your post title in the page header (title).
* **Added** - Grid/list buttons to the catalog products in the shop page.
* **Added** - Links in the shop page to show the number of products.
* **Added** - New color options in WooCommerce > Advanced Styling to customize the toolbar of the shop page.
* **Added** - New color options in WooCommerce > Advanced Styling to customize the title and product description into the tabs.
* **Added** - German language, thank you very much to Andreas Schu.
* **Added** - Breadcrumbs in the blog page.
* **Tweak** - Footer page ID, now you can add a page created with Elementor or Beaver Builder or any other page builder.
* **Tweak** - All output logo improved.
* **Fixed** - RTL problem with the carousel of posts galleries and products, I changed the script by Slick.
* **Fixed** - There was a conflict with the select2 script (used to select a typography in the customizer) when WooCommerce was enabled because their version of the script is older.
* **Removed** - Unnecessary elements in the front end of Elementor's post-type Library.
* **Removed** - I deleted "$j( document ).ready( function() {" from the "Custom JS" option so that you can have full control of the code you enter.

### *2016.12.20* - 1.1.0
Warning: The name of the theme changed to OceanWP because Ocean was already taken, WordPress will see the OceanWP theme as a new theme, so, you need to do a fews steps, look at this video:
https://youtu.be/s5TUYhUMc-8

1. In your WordPress dashboard, go to Theme Panel > Import/Export, and click on the export button, this will generate a json file.
2. Install and activate the Widget Importer & Exporter plugin and go to Tools > Widget Import/Export to export your widgets.
3. Download the new version of the theme on oceanwp.org.
4. Return to your WordPress dashboard and upload the new version.
5. If not already done, update WordPress, then, update all extensions.
6. Go to Theme Panel > Import/Export and import the json file of the step 1.
7. Go to Appearance > Widgets and delete all your widgets to prevent conflicts (optional).
8. Go to Tools > Widget Import/Export and import the .wie file exported to the step 2.
9. Check that everything is ok on your site, if so, go back to Appearance > Themes and delete the old Ocean theme.
10. if you use a child theme, replace "wp_get_theme( 'Ocean' )" by "wp_get_theme( 'OceanWP' )".

Do not worry, all your changes made to the theme will not be affected because I've not modified any filters, action or theme_mods.
I'm really sorry for that, there will never be any changes of this kind again, I want the theme to be available in the WordPress directory, and the name Ocean was already taken in the waiting list, so I had to modify it to OceanWP.

Do not hesitate to contact me via facebook or trough the support page if you have misunderstood or you are having an issue.

* **Added** - New color option in the customizer to add a background to the transparent header style.
* **Added** - Select2 script for the typography select.
* **Added** - Typography for the H1, H2, H3 and H4 headings.
* **Added** - New panel to add your own JS code directly into the customizer.
* **Added** - New field in the customizer to add your own padding left/right for the menu items.
* **Added** - New field in the customizer to add your own width for the dropdrow menu.
* **Added** - function_exists to all functions in the helpers file, so you can alter them via the child theme.
* **Tweak** - Large enhancement of the customizer options.
* **Updated** - Font Awesome icons to 4.7.
* **Deleted** - Options in the customizer to choose your links color between light and dark for the transparent header, you can choose your own color in the menu section.
* **Fixed** - Problem to change the font size, font weight, letter spacing, etc, to the center header style.
* **Fixed** - Problem with the button to open the mobile menu.

### *2016.12.12* - 1.0.9.1
* **Fixed** - Problem with the customizer.

### *2016.12.07* - 1.0.9
* **Added** - Support WordPress 4.7.
* **Fixed** - Problem with the menu items in WordPress 4.7.
* **Tweak** - Migrate the custom CSS of the Theme Panel into the new Additional CSS panel of the customizer.

### *2016.12.01* - 1.0.8.1
* **Fixed** - Small issue.

### *2016.12.01* - 1.0.8
* **Added** - New fields in the customizer to add a background image.
* **Added** - Option in the customizer to control the max width of the logo.
* **Added** - New fields in the customizer to add a padding top and bottom at the header.
* **Added** - Tagline in the Site Identity section of the customizer.
* **Added** - Selective refresh to widgets.
* **Added** - Option to add a color to the overlay page header.
* **Fixed** - Problem with the overlay of the page header.
* **Fixed** - Problem to change the font size of the menu items for the Top Menu header style.
* **Tweak** - Moved Site Icon field to the Site Identity section of the customizer.
* **Tweak** - Some files improvement.

### *2016.11.26* - 1.0.7
* **Added** - New fields in the Blog section of the customizer to show/hide elements in the single post.
* **Tweak** - Icon search and cart replaced by text for the center header style.
* **Fixed** - Problem categories posts in megamenu.

### *2016.11.21* - 1.0.6
* **Added** - New header style "Center".
* **Fixed** - Problem anchor links on mobile menu.
* **Fixed** - Problem megamenu category posts on full screen header style.

### *2016.11.12* - 1.0.5
* **Added** - Boxed layout.
* **Added** - Options in the Customizer to alter the meta in blog entries and single.

### *2016.11.11* - 1.0.4
* **Added** - New header style "Full Screen".
* **Added** - New posts style "Grid".
* **Added** - New blog pagination "Infinite Scroll".
* **Added** - Function to add an overlay color to the page header background image style.
* **Fixed** - Problem breadcrumbs on the home page.
* **Fixed** - Breadcrumbs position problem on centered page title.
* **Tweak** - Redirection to the welcome page during the theme activation.

### *2016.11.05* - 1.0.3
* **Added** - New fields in the Contact Info widget to add your own titles and icons.
* **Tweak** - PHP files.

### *2016.11.02* - 1.0.2
* **Added** - New header style "Top Menu".
* **Added** - New widget "Recent Posts".
* **Added** - New "Shortcode" field in the Ocean Settings metabox to add your slider shortcode below the header.
* **Added** - Function to add custom fonts.
* **Added** - Function to delete term data when a term is deleted.
* **Added** - Option to the categories menu items to add your latest posts in mega menu.
* **Tweak** - Improvements of the newsletter widget.
* **Fixed** - Lightbox images into the content.
* **Fixed** - Problems of tabs in the editor mode of Elementor and Beaver Builder when you set the page in full screen.
* **Fixed** - Problem posts and related posts image link.
* **Fixed** - The top bar social alt work perfectly now.

### *2016.10.16* - 1.0.1
* **Added** - Options in the customizer to change the colors of WooCommerce pages.

### *2016.10.13* - 1.0.0
* Initial release
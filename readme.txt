=== Plugin Name ===
Contributors: terrytsang
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=terry@terrytsang.com&item_name=Donation+for+TerryTsang+Wordpress+WebDev
Plugin Name: WooCommerce Custom Direct Checkout
Plugin URI:  http://terrytsang.com/shop/shop/woocommerce-direct-checkout/
Tags: woocommerce, custom fields, direct, checkout, e-commerce
Requires at least: 2.7
Tested up to: 3.8.1
Stable tag: 1.0.5
Version: 1.0.5
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

You can skip shopping cart page and implement add to cart button redirect to checkout page or you can redirect to other existing page.

== Description ==

A WooCommerce plugin that aims to simplify the checkout process, leading to an immediate increase in sales.

In WooCommerce Settings Panel, there will be a new submenu link called 'Direct Checkout' where you can:

*   Enabled / Disabled the direct checkout option
*   Change "Add to cart" to any text
*   Update "Redirect to Page" option (NEW)

= Features =

*   Implement add to cart button redirect to checkout page pattern
*   2 languages available : English UK (en_GB) and Chinese (zh_CN)

= IMPORTANT NOTES =
*   Do use POEdit and open 'wc-direct-checkout.pot' file and save the file as wc-direct-checkout-[language code].po, then put that into languages folder for this plugin.
*   Please uncheck the option "Enable AJAX add to cart buttons on archives" at WooCommerce > Settings > Catalog to make the rediection working without ajax.

= GET PRO VERSION =
http://terrytsang.com/shop/shop/woocommerce-direct-checkout-pro/

= Additional Plugins by Terry Tsang =
*   [Custom Checkout Options] (http://terrytsang.com/shop/shop/woocommerce-custom-checkout-options/)
*   [Social Buttons PRO] (http://terrytsang.com/shop/shop/woocommerce-social-buttons-pro/)
*   [Extra Fee Options PRO] (http://terrytsang.com/shop/shop/woocommerce-extra-fee-option-pro/)


== Installation ==

1. Upload the entire *woocommerce-direct-checkout* folder to the */wp-content/plugins/* directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to WooCommerce Settings panel at left sidebar menu and update the options at Tab *Direct Checkout* there.
4. That's it. You're ready to go and cheers!

== Screenshots ==

1. [screenhot-1.png] Screenshot Admin WooCommerce Settings - Direct Checkout options
2. [screenhot-2.png] Screenshot Frontend WooCommerce - Catalog page
3. [screenhot-3.png] Screenshot Frontend WooCommerce - Product page

== Changelog ==

= 1.0.5 =

* Updated "Add to cart" filter with WooCommere v2.1.x
* Fixed table width problem for option settings page

= 1.0.4 =

* Added pro version link 

= 1.0.3 =

* Updated reademe file for instruction and notes


= 1.0.2 =

* Update 'Redirect to Page' option
* Updated table style for Firefox display bugs

= 1.0.1 =

* Add 'Redirect to Page' option, let user choose redirecting to any page after add to cart pressed
* Updated wrong hyperlink

= 1.0.0 =

* Initial Release
* Customize add to cart text and change add to cart function directly to checkout page


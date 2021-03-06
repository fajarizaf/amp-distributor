=== GazChap's WooCommerce Purchase Order Payment Gateway ===
Contributors: gazchap
Tags: woocommerce,ecommerce,gateway,purchase order,payment,offline,invoice
Requires at least: 4.2.0
Requires PHP: 5.3
Tested up to: 4.9.8
License: GNU General Public License v2.0
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Stable tag: trunk
Donate link: https://paypal.me/gazchap

Adds a Purchase Order payment gateway to WooCommerce.

== Description ==
This plugin adds a new offline payment gateway to WooCommerce that allows your customers to request an invoice with a Purchase Order.

There are a number of options:

* You can set the plugin to ask the customer for a Purchase Order Number, and dictate whether this is mandatory or can be left blank.
* You can set the plugin to ask the customer for a postal address for the invoice.
* You can set the plugin to pre-fill this address with the customer's existing billing address (if they are logged in, and have one set in WooCommerce)
* You can set the plugin to add supplied Purchase Order information to order notification emails

When an order is received, the plugin will add all of the submitted information on to the WooCommerce View Order screen.

Note: This plugin does not (currently, at least) generate the actual invoices - it is only used to collect the Purchase Order information.

== Requirements ==

[WordPress](https://wordpress.org). Tested up to version 4.9.8.
[WooCommerce](https://woocommerce.com). Tested with versions up to 3.4.4, minimum version is 3.0.0.

== Installation ==

Install via the WordPress Plugin Directory, or download a release from this repository and install as you would a normal WordPress plugin.

== Usage ==

Once installed and activated, you need to enable the Payment Gateway in *WooCommerce > Settings > Checkout* (or via the plugin's Settings link on the WordPress Plugins page) - you can then set the various options for the plugin at the same time.

== Changelog ==
= 1.1 (26/08/2018) =

* **Bugfix:** Purchase Order metadata is now saved to the order before emails are triggered to be sent.
* **New:** Setting to add the supplied Purchase Order Number to the email notifications
* **New:** Setting to add the supplied Purchase Order Address to the email notifications

= 1.0 (21/02/2018) =

* Initial release.

== License ==
Licensed under the [GNU General Public License v2.0](http://www.gnu.org/licenses/gpl-2.0.html)


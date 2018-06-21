# WooCommerce Subscriptions Backstage

Using [WooCommerce Subscriptions](https://woocommerce.com/products/woocommerce-subscriptions/) with a plugin, like WPML, that allows you to set duplicate URLs for the single copy of your WordPress application?

By default, when WooCommerce Subscriptions detects a change in a site's URL, it switches to [_Staging Mode_](https://docs.woocommerce.com/document/subscriptions-handles-staging-sites/). In _Staging Mode_, all subscriptions are forced to use [manual renewals](https://docs.woocommerce.com/document/subscriptions/renewal-process/). This prevents accidental, duplicate renewal payments being processed by staging sites.

On occasion, there is a need to run the one copy of the site's database and WordPress application on different URLs. For example, using WPML to have different URLs for the site in different languages.

This plugin can be used to disable WooCommerce Subscriptions' Staging Mode completely.

**User beware:** Usage of this plugin requires manual intervention when creating duplicate copies of your site for staging or development. Never leave this plugin active on a site where live payments should not be processed.

## Usage

1. Download the [latest version of the plugin](https://github.com/Prospress/woocommerce-subscriptions-backstage/archive/master.zip)
1. [Install & activate](https://codex.wordpress.org/Managing_Plugins#Installing_Plugins) the plugin

[Automatic renewal payments](https://docs.woocommerce.com/document/subscriptions/renewal-process/) will then be triggered for all subscriptions with an automatic payment method, no matter what URL the site is using.

## Reporting Issues

If you find an problem, please [open a new Issue](https://github.com/Prospress/woocommerce-subscriptions-backstage/issues/new).

Please note, we will not help address issues that are a result of ignoring the above warning and not manually disabling the plugin on sites where live payments should not be processed.

---

<p align="center">
	<a href="https://prospress.com/">
		<img src="https://cloud.githubusercontent.com/assets/235523/11986380/bb6a0958-a983-11e5-8e9b-b9781d37c64a.png" width="160">
	</a>
</p>
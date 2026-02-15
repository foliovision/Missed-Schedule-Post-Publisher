# Missed Schedule Post Publisher

![WordPress Plugin Version](https://img.shields.io/badge/version-2.3-blue.svg)
![WordPress Compatibility](https://img.shields.io/badge/wordpress-5.3%2B-brightgreen.svg)
![PHP Compatibility](https://img.shields.io/badge/php-7.0%2B-purple.svg)
![License](https://img.shields.io/badge/license-GPLv2-red.svg)
[![WP compatibility](https://plugintests.com/plugins/wporg/missed-schedule-post-publisher/wp-badge.svg)](https://plugintests.com/plugins/wporg/missed-schedule-post-publisher/latest)
[![PHP compatibility](https://plugintests.com/plugins/wporg/missed-schedule-post-publisher/php-badge.svg)](https://plugintests.com/plugins/wporg/missed-schedule-post-publisher/latest)
[![Update Status](https://img.shields.io/badge/Status-Actively%20Maintained-green.svg)](https://github.com/ufukart/Missed-Schedule-Post-Publisher)
![GitHub last commit](https://img.shields.io/github/last-commit/ufukart/Missed-Schedule-Post-Publisher)
![Visitors](https://api.visitorbadge.io/api/visitors?path=https://github.com/ufukart/Missed-Schedule-Post-Publisher%2F&label=HITS&countColor=%23263759&style=flat)
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/donate/?business=53EHQKQ3T87J8&no_recurring=0&currency_code=USD)

🎯 Never miss scheduled posts again! Automatically detects and publishes missed scheduled posts on time, every time - perfect for low-traffic websites.

---

## 📖 Description

**Your Scheduled Posts, Published On Time - Guaranteed!**

Have you ever scheduled a post in WordPress, only to find it still sitting in "Missed Schedule" status hours or days later? You're not alone! This frustrating issue affects thousands of WordPress sites, especially those with low traffic.

Missed Schedule Post Publisher is the ultimate solution to WordPress's unreliable scheduling system. Install it once, configure your preferred check interval, and never worry about missed posts again!

### 🔴 The Problem: WordPress's Scheduling Flaw

WordPress doesn't use a true cron system to publish scheduled posts. Instead, it relies on **visitor activity** to trigger scheduled tasks. This means:

* **Low-traffic sites** can miss scheduled posts for hours or even days
* **Nighttime posts** may not publish until someone visits your site
* **Time-sensitive content** might go live too late to be effective
* **Editorial calendars** become unreliable and unpredictable

If your site doesn't get constant traffic, you're at risk of the dreaded "Missed Schedule" error.

### ✅ The Solution: Reliable, Automatic Publishing

Missed Schedule Post Publisher runs automatically at your chosen interval, checking for any posts that should have been published but weren't. When it finds them, it publishes them immediately—no manual intervention required!

---

## 🌟 Key Features

### ⏰ Automatic Missed Post Detection
Continuously monitors your scheduled posts and instantly detects any that have missed their publication time. No more manually checking your posts list!

### 🎛️ Customizable Check Intervals
Choose how frequently the plugin checks for missed posts: **5, 10, 15, 20, 30, or 60 minutes**. Match the interval to your site's needs and traffic patterns.

### 🚀 Set It and Forget It
Once configured, the plugin works silently in the background. Your posts will be published on time, every time, without you having to think about it.

### 🔄 Smart Dual-Mode Operation
Works seamlessly with **both WP-Cron enabled and disabled environments**. If WP-Cron is disabled on your server, the plugin automatically switches to page-visit-based checking with intelligent throttling. No configuration needed—it just works!

### 🌐 DISABLE_WP_CRON Compatible
Perfect for **shared hosting, high-traffic sites with aggressive caching, or server-level cron setups**. When WP-Cron is disabled, the plugin runs efficiently on page visits without impacting performance.

### 📊 Perfect for Low-Traffic Sites
Specifically designed for blogs, personal websites, and business sites that don't receive constant visitor traffic. Ensures your content strategy stays on track.

### ⚡ Lightweight & Efficient
Uses minimal server resources with optimized database queries. Won't impact your site's performance, speed, or analytics data.

### 🔒 Enterprise-Grade Security
Built with WordPress best practices, including proper sanitization, nonce verification, and capability checks. Your site stays secure.

### 🌍 Translation Ready
Fully internationalized with i18n support. Ready to work in any language with proper translations.

### 🔧 WordPress Cron Integration
Leverages WordPress's cron system for reliable scheduling when available, ensuring checks happen consistently even during low-traffic periods.

### 📱 Works Everywhere
Compatible with all modern WordPress themes, caching plugins, and hosting environments. No conflicts, just results.

---

## 💡 Why You Need This Plugin

### For Bloggers & Content Creators
Maintain a consistent publishing schedule even if you're not online 24/7. Your audience expects fresh content at specific times—deliver it reliably.

### For Business Websites
Time-sensitive announcements, product launches, and promotional content must go live on schedule. Don't risk delays that could cost you customers.

### For Marketing Teams
Coordinate content releases across multiple channels without worrying about WordPress letting you down. Your editorial calendar becomes trustworthy again.

### For Low-Traffic Sites
If you're building a new site or running a niche blog, you can't rely on visitor traffic to trigger your posts. This plugin ensures every post goes live on time.

### For Peace of Mind
Stop manually checking if your scheduled posts went live. Stop worrying about the "Missed Schedule" error. Just focus on creating great content.

---

## 📥 Installation

### 🔽 Automatic Installation (Recommended)

1. Log in to your WordPress admin dashboard
2. Navigate to **Plugins → Add New**
3. Search for "**Missed Schedule Post Publisher**"
4. Click **Install Now** next to the plugin
5. Click **Activate** once installation is complete
6. Go to **Settings → Missed Schedule Post Publisher** to configure

### 📦 Manual Installation

1. Download the plugin ZIP file from WordPress.org
2. Go to **Plugins → Add New → Upload Plugin**
3. Click **Choose File** and select the downloaded ZIP
4. Click **Install Now**
5. After installation, click **Activate Plugin**
6. Navigate to **Settings → Missed Schedule Post Publisher**

### ⚙️ Configuration Setup

1. Once activated, go to **Settings → Missed Schedule Post Publisher**
2. Select your preferred check interval from the dropdown menu:
   * **5 minutes** - For time-critical content and active sites
   * **10 minutes** - Balanced option for most sites
   * **15 minutes** - Good for regular blogs
   * **20-30 minutes** - For less frequent publishing schedules
   * **60 minutes** - For sites with occasional scheduled posts
3. Click **Save Settings**
4. You're done! The plugin will now monitor and publish missed posts automatically

### 🎉 That's It!

The plugin works silently in the background. You can update your settings anytime, and you'll see a confirmation message when settings are saved.

---

## ❓ Frequently Asked Questions

### 🤔 What exactly does this plugin do?

The plugin automatically detects WordPress posts that were scheduled to be published but missed their publication time due to the "Missed Schedule" error. It then publishes these posts immediately, ensuring your content goes live as intended.

### ❓ Why do scheduled posts sometimes fail to publish in WordPress?

WordPress uses a pseudo-cron system that relies on visitor activity to trigger scheduled tasks. If your site doesn't receive visits during the time a post is scheduled, WordPress may fail to publish it. This is especially common on:
* New or low-traffic websites
* Sites scheduling posts during off-peak hours
* Blogs with irregular visitor patterns
* Websites behind aggressive caching

### ⏱️ How often does the plugin check for missed posts?

You have complete control! Choose from check intervals of 5, 10, 15, 20, 30, or 60 minutes. Select the frequency that matches your publishing needs and traffic patterns.

### 🔧 What if my hosting provider has DISABLE_WP_CRON enabled?

No problem! **This is one of the key features of version 2.3+**. The plugin automatically detects if WP-Cron is disabled and switches to a fallback mode that runs on page visits. You'll see a notice in the admin panel confirming this mode is active. The plugin uses intelligent throttling to ensure it only runs at your configured interval, regardless of how many page visits occur.

### 🚀 Will the plugin work on heavily cached sites?

Absolutely! Many caching plugins (like WP Rocket, W3 Total Cache) or CDN services (like Cloudflare) can prevent WP-Cron from triggering. Version 2.3+ handles this automatically by also checking during regular page visits. This dual approach ensures your posts are published even if WP-Cron is blocked by caching.

### ⚙️ Does this plugin require server cron setup?

No! Unlike some alternatives, you don't need SSH access or server cron configuration. The plugin works perfectly with WordPress's built-in cron system, and if that's disabled, it falls back to page-visit-based checking. It's a true "install and forget" solution.

### 📊 How can I tell which mode the plugin is using?

Go to **Settings → Missed Schedule Post Publisher**. The admin panel clearly shows:
* If WP-Cron is disabled, you'll see: "⚠️ WP-Cron is disabled on this server. The plugin will automatically run when visitors browse your site instead."
* Current operating mode: Either "Running on: Page visits" or showing the next scheduled cron run time
* Last check execution time

### 🏎️ Will page-visit mode slow down my site?

Not at all! The plugin uses intelligent throttling—it only runs when your configured interval has passed. If the last check was 5 minutes ago and you've set a 15-minute interval, it won't run again for another 10 minutes, no matter how many visitors arrive. Plus, it only runs on frontend pages, never in the admin panel.

### 🐌 Will this plugin slow down my website?

No! The plugin is extremely lightweight and only performs a quick database query at your chosen interval. It's optimized for minimal resource usage and won't affect your site's loading speed or performance. Your visitors won't notice any difference.

### 📊 Does it affect my site analytics?

Not at all. The plugin works in the background and doesn't generate additional page views or affect your analytics data. Your traffic statistics remain accurate.

### 📝 Does it work with custom post types?

Yes! As of version 2.0, the plugin automatically detects and handles all public Custom Post Types. This includes WooCommerce products, Event Calendar items, Portfolio items, and any other custom content types you have on your site.

### 🚀 Can I use this on a high-traffic website?

Yes, absolutely! While the plugin is designed primarily for low-traffic sites where the "Missed Schedule" problem is most common, it works perfectly on high-traffic websites too. It adds an extra layer of reliability to your publishing workflow.

### 🔧 How do I configure the plugin after installation?

Simply go to **Settings → Missed Schedule Post Publisher** in your WordPress admin panel. Select your preferred check interval from the dropdown menu and click Save Settings. That's all you need to do!

### 💾 Is it compatible with caching plugins?

Yes! The plugin is compatible with all major caching plugins including WP Rocket, W3 Total Cache, WP Super Cache, and others. Version 2.3+ adds enhanced compatibility with automatic fallback when WP-Cron is blocked by caching.

### 🛠️ The plugin isn't working - what should I do?

Try these troubleshooting steps:

1. **Check for missed posts**: Ensure you actually have posts with "Missed Schedule" status (go to Posts → All Posts and check the status)
2. **Verify settings**: Confirm the plugin is activated and configured with a check interval
3. **Check admin panel**: Go to Settings → Missed Schedule to see which mode is active (WP-Cron or page visits)
4. **Clear cache**: If using a caching plugin, clear your cache completely
5. **Check for conflicts**: Temporarily disable other plugins to see if there's a conflict
6. **Plugin refresh**: Try deactivating and reactivating the plugin
7. **Check error logs**: Look at your WordPress debug log for any error messages
8. **Contact support**: If the issue persists, reach out via the support forum

### 🔐 Is this plugin secure?

Yes! Built with WordPress security best practices:
* Proper input sanitization and validation
* Nonce verification for all admin actions
* SQL injection protection using `$wpdb->prepare()`
* Capability checks for admin operations
* Try-catch-finally error handling to prevent lock issues

### 🌐 Can I translate this plugin to my language?

Absolutely! The plugin is fully internationalized and ready for translation. You can use tools like Poedit or Loco Translate to create translations for your language.

### 💰 Is there a premium version?

Currently, this plugin is completely free with all features included. If you find it useful, please consider [leaving a 5-star review](https://wordpress.org/support/plugin/missed-schedule-post-publisher/reviews/) or [supporting development](https://www.paypal.com/donate/?business=53EHQKQ3T87J8&no_recurring=0&currency_code=USD)!

### 🆘 Where can I get support?

For support, feature requests, or bug reports, please visit the [WordPress.org support forum](https://wordpress.org/support/plugin/missed-schedule-post-publisher/). We monitor the forums regularly and respond to all inquiries.

---

## 📸 Screenshots

1. Simple, intuitive settings page - choose your check interval
2. Confirmation message when settings are saved
3. Plugin settings link directly from the plugins page
4. Automatic publishing of missed scheduled posts
5. WP-Cron status indicator and operating mode display (v2.3+)

---

## 📝 Changelog

### 2.3 - Critical Reliability Update 🚀

**Release Date:** February 15, 2026

This is a **major reliability update** that solves the #1 cause of "plugin not working" reports: disabled WP-Cron and aggressive caching.

#### 🎯 New Features

**✨ Smart Dual-Mode Operation**
* **Automatic DISABLE_WP_CRON detection** - Plugin now works perfectly even when WP-Cron is disabled
* **Page-visit fallback mode** - If WP-Cron doesn't trigger, the plugin runs on frontend page visits instead
* **Intelligent throttling** - Ensures checks only happen at your configured interval, preventing performance impact
* **Zero configuration required** - Automatically detects the best method and switches seamlessly

**🛡️ Enhanced Reliability**
* **Try-catch-finally protection** - Prevents lock mechanism from getting stuck even if fatal errors occur
* **Improved error handling** - Better logging and recovery from unexpected failures
* **Lock cleanup guarantee** - Transient lock is always released, even if the script crashes

**📊 Admin Panel Improvements**
* **WP-Cron status indicator** - Shows if WP-Cron is disabled with a clear notice
* **Operating mode display** - See at a glance whether plugin is using WP-Cron or page visits
* **Better status information** - More informative "Current Status" section in settings

#### 🔧 Technical Improvements

* Added `check_and_publish_on_page_load()` method for page-visit-based checking
* Wrapped `publish_missed_posts()` in try-catch-finally for bulletproof lock management
* Added intelligent throttling to prevent excessive execution on high-traffic sites
* Admin panel now skipped during page-visit checks to reduce overhead
* Enhanced compatibility with caching plugins (WP Rocket, W3 Total Cache, Cloudflare, etc.)

#### 🐛 Bug Fixes

* **Fixed:** Plugin not working when `DISABLE_WP_CRON = true` in wp-config.php
* **Fixed:** Lock mechanism getting stuck after fatal errors or timeouts
* **Fixed:** No fallback when WP-Cron is blocked by aggressive caching
* **Fixed:** Plugin remaining silent on low-traffic sites with caching enabled

#### 💡 Why This Update Matters

**Before 2.3:**
* ❌ If WP-Cron was disabled → Plugin didn't work at all
* ❌ Full-page caching → WP-Cron never triggered → Posts never published
* ❌ Low traffic + caching → Scheduled posts missed indefinitely
* ❌ Lock gets stuck → Plugin stops working until manual intervention

**After 2.3:**
* ✅ Works with WP-Cron enabled OR disabled
* ✅ Works with any caching plugin or CDN
* ✅ Works on low-traffic sites
* ✅ Never gets stuck - self-recovering
* ✅ True "set and forget" reliability

#### 🎯 Who Should Update?

**EVERYONE should update to 2.3**, but especially if you:
* Use shared hosting (often has DISABLE_WP_CRON enabled)
* Use caching plugins like WP Rocket, W3 Total Cache, or similar
* Use CDN services like Cloudflare that cache aggressively
* Have a low-traffic site or blog
* Schedule posts during off-peak hours
* Have experienced "plugin not working" in the past

---

### 2.2
* **🔧 Improvements**
Fixed plugin activation and deactivation logic to fully comply with WordPress standards.
Moved register_activation_hook and register_deactivation_hook outside the constructor and bound them using static class methods for deterministic behavior.
Ensured default plugin options are created on activation, even if the admin page is never visited.
Improved cron scheduling reliability by preventing duplicate or missing cron events.

* **🧹 Cleanup**
Plugin options are now cleanly removed on deactivation, leaving no residual data in the database.
Improved cron cleanup to ensure no orphaned scheduled events remain after deactivation.

### 2.1
* **🔒 Security**
Fixed a security issue where admin settings could be updated before capability checks.
Capability (manage_options) validation is now performed before processing POST requests.
Added additional hardening to prevent unauthorized settings updates.

* **⏰ Bug Fixes**
Fixed an incorrect timezone calculation that caused double GMT offset conversion in admin UI.
Replaced manual date offset logic with WordPress-native time handling for accurate timezone and DST support.

* **🧩 Improvements**
Improved admin page logic for safer and more predictable settings handling.
Internal code cleanup to better align with WordPress coding and security best practices.

### 2.0
* **New:** Added support for all public Custom Post Types (CPT), WooCommerce products, and Events.
* **Improved:** Implemented batch processing (limit 10) to prevent server timeouts on large queues.
* **Improved:** Admin interface now shows "Last Run" and "Next Run" times in the website's Local Timezone instead of GMT.
* **Fixed:** Fixed internationalization issue; translation files now load correctly.
* **Tweak:** Adjusted cron scheduling logic to avoid conflicts on activation.

### 1.0.6
* **Fixed:** Failsafe cron mechanism now uses recurring events instead of single events
* **Fixed:** SQL query now orders posts by date to publish oldest first
* **Fixed:** XSS vulnerabilities with proper escaping functions
* **Fixed:** CSRF security with proper nonce verification failure handling
* **Fixed:** Error handling for failed post publishing with error logging
* **Fixed:** Type safety with explicit integer casting
* **Improved:** Added error logging for debugging
* **Improved:** User feedback after saving settings
* **Improved:** Admin UI now shows next scheduled run time
* **Improved:** Better form layout using WordPress standards

### 1.0.5 - Major Security & Performance Update

#### 🔒 Security Enhancements
* **Fixed critical SQL injection vulnerability** using `$wpdb->prepare()` for all database queries
* **Added comprehensive nonce verification** for all admin form submissions
* **Implemented capability checks** to ensure only authorized users can modify settings
* **Strengthened input sanitization** for all user-submitted data

#### 🏗️ Code Architecture Improvements
* **Complete code refactoring** using Object-Oriented Programming (OOP) architecture
* **Improved code organization** with separate classes for admin and public functionality
* **Better separation of concerns** making the codebase more maintainable
* **Added comprehensive inline documentation** for developers

#### ⚡ Performance Optimizations
* **Optimized database queries** for faster scheduled post detection
* **Reduced unnecessary hook registrations** to minimize overhead
* **Improved memory usage** with better variable handling and cleanup
* **More efficient cron scheduling** for reliable execution

#### 🌍 Internationalization
* **Full i18n support** - Plugin is now translation-ready
* **Proper text domain usage** throughout the codebase
* **Ready for translation** into any language

#### 🎨 User Interface Improvements
* **Enhanced admin interface** with clearer labels and instructions
* **Better user feedback** with improved success/error messages
* **Cleaner settings page** design for better usability
* **Added helpful tooltips** and descriptions

#### 🐛 Bug Fixes
* **Fixed timezone handling issues** that could cause incorrect post scheduling
* **Resolved potential race conditions** in the post publishing process
* **Fixed admin notice display problems** that could show notices on wrong pages
* **Corrected timing issues** with cron execution

#### 🔧 Technical Improvements
* **Tested with PHP 8.4** - Fully compatible with the latest PHP version
* **Updated minimum WordPress version** requirements
* **Improved error handling** throughout the plugin
* **Better logging** for debugging purposes

### 1.0.4
* **Added:** Quick Settings link on the plugins page for easy access
* **Added:** Donate link to support continued development
* **Improved:** Plugin action links organization

### 1.0.3
* **Compatibility:** Fully tested and compatible with PHP 5.6 through PHP 8.2
* **Improved:** Code optimization for better PHP 8.x compatibility
* **Improved:** Minor performance enhancements
* **Fixed:** Deprecated function warnings in PHP 8.x

### 1.0.2
* **Fixed:** Critical bug causing "Undefined Index" warning in some configurations
* **Improved:** Error handling for edge cases

### 1.0.1
* **Changed:** Removed plugin menu from WordPress Toolbar for cleaner interface
* **Changed:** Moved settings menu under WordPress Settings section
* **Improved:** Better menu organization and accessibility

### 1.0 - Initial Release
* 🎉 **First public release**
* ✅ Automatic detection of missed scheduled posts
* ✅ Customizable check intervals (5, 10, 15, 20, 30, 60 minutes)
* ✅ Simple, user-friendly settings interface
* ✅ Lightweight and performance-optimized
* ✅ Compatible with all major WordPress themes and plugins

---

## ⚠️ Upgrade Notice

### 2.3
**CRITICAL RELIABILITY UPDATE!** This version fixes the #1 cause of "plugin not working" complaints. Now works even when WP-Cron is disabled (common on shared hosting) and with aggressive caching. Features automatic fallback to page-visit checking, enhanced error recovery, and bulletproof lock management. **If you've ever had the plugin "stop working" - this update fixes it!** All users should update immediately for maximum reliability.

### 2.0
Major update! Now supports Custom Post Types (CPT) & WooCommerce. Added batch processing for better performance and fixed timezone displays.

### 1.0.5
**IMPORTANT SECURITY UPDATE!** This version fixes critical security vulnerabilities including SQL injection protection. Update immediately! Also includes major performance improvements and full WordPress 6.9 compatibility.

### 1.0.4
Minor update with improved plugin management features. Update recommended.

### 1.0.3
PHP 8.2 compatibility update. Recommended for all users on modern PHP versions.

### 1.0.2
Bug fix update. Resolves undefined index warning. Update recommended.

### 1.0.1
Improved user interface with better menu organization. Update recommended.

---

## 💝 Support This Plugin

If Missed Schedule Post Publisher has saved you time and frustration, please consider:

* ⭐ **[Leave a 5-star review](https://wordpress.org/support/plugin/missed-schedule-post-publisher/reviews/)** - Help others discover this solution
* 🐛 **[Report bugs or request features](https://wordpress.org/support/plugin/missed-schedule-post-publisher/)** - We value your feedback
* ☕ **[Buy me a coffee](https://buymeacoffee.com/ufukart)** - Support continued development
* 💰 **[Donate via PayPal](https://www.paypal.com/donate/?business=53EHQKQ3T87J8&no_recurring=0&currency_code=USD)** - Support continued development
* 📢 **Share with others** - Help fellow WordPress users avoid the "Missed Schedule" nightmare

---

## 🤝 About the Developer

Created by **UfukArt** - Passionate about solving real WordPress problems with elegant, reliable solutions.

### Other WordPress Plugins:
* **[OptimWP](https://wordpress.org/plugins/optimwp/)** - WordPress Optimization Toolkit
* **[Comment Approved Notifier Extended](https://wordpress.org/plugins/comment-approved-notifier-extended/)** - The Comment Approved Notifier Extended plugin for WordPress automatically sends an email notification to the comment author when their comment is approved on your website.

### Links
* [Plugin Page on WordPress.org](https://wordpress.org/plugins/missed-schedule-post-publisher/)
* [Support Forum](https://wordpress.org/support/plugin/missed-schedule-post-publisher/)
* [Developer Website](https://www.zumbo.net)

---

## 📄 License

This plugin is licensed under the GPLv2 or later.

```
Copyright (C) 2024 UfukArt

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.
```

---

**Your scheduled posts deserve better than WordPress's default system. Install Missed Schedule Post Publisher today and publish with confidence! 🚀**

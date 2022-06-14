# Update 15.0.0 - 7 May, 2022

The logo, favicon & opengraph of the site will have to be re-added after the update due to an upgrade to the related handling system.
Implemented the ability to enable/disable auto language detection via the admin panel.
Implemented the ability to set a different logo base on the theme style (dark or light).
Implemented the ability to set a different logo for emails.
Implemented the ability to reset statistics.
Implemented RTL support for emails & improved the email templates looks.
Implemented the ability to create multi-language pages from the admin panel.
Implemented API endpoint for custom domains.
Implemented an anti-phishing system code for emails sent out to users by the system.
Implemented cookie consent logging feature to store proof of given consent.
Implemented cookie consent logging export to CSV.
Implemented cookie consent settings link in the footer, so that people can change their given consent at all times.
Updated the rrweb library to the 1.1.2 release, now the standard tracking code is 50% lighter.
Improved & added more widget details to the replay page.
Added avg. recorded events & avg. duration per replay details to the replays list.
Contact form, you can now reply-to via your email client directly via the sent email.
Resend activation page will now be disabled if the email confirmation setting is disabled.
Reworked and improved the Sitemap to include more pages, dynamically.
Improved the pages resources center UI & fixed small bugs.
Reworked and improved the language & dark mode switcher.
All user sessions will be logged out if the account changes password (security improvement).
Fixed Mollie annual payments not processing correctly.
Fixed reset password not working for some particular emails & not logging the user in after the password change.
Fixed language preference of a user being reset when re-logging in.
Fixed admin impersonation of user logout not working properly.
Update 14.0.0 - 16 March, 2022

Implemented Cookie Consent functionality, highly configurable via the admin panel and translation system.
Implemented Discord login functionality, configurable via the admin panel.
Implemented Paddle payment gateway for one-time payments.
Implemented the ability to generate discount/redeemable codes in bulk via the admin panel.
Implemented new dedicated code redeeming page.
Implemented the ability to set links (from the admin panel) to open in a new tab.
Implemented the ability to enable/disable a language via the admin panel.
Implemented the ability to filter translated, non translated and all strings when editing a language via the admin panel.
Fully reworked the account related pages for better looks and consistency over the altumcode products.
Fixed payments list filters not working for all processors.
Fixed payment generation issue in some special cases for a few payment gateways.
Fixed various new translation system issues.
Multiple other visual, functional improvements & bugfixes.
Update 13.1.0 - 3 February, 2022

ℹ️ If you want to migrate your translated languages to the new system, use the migration tool.
Implemented the ability to delete a language from the admin panel.
Language names can now contain UTF8 special characters.
Fixed language update bug.
Fixed links not working from sent emails.
Update 13.0.0 - 2 February, 2022

Fully reworked the Languages & Translations system for much better performance, handling and usability.
Implemented the ability to edit and translate Languages from the admin panel.
Implemented Crypto.com one-time payment gateway.
Update 12.0.0 - 24 January, 2022

Implemented custom domains system to allow users to bypass ad-blockers with custom domains/subdomains tracking pixels.
Implemented custom domains management page in the admin panel.
Implemented custom domains management page in the user app panel.
Implemented custom domains admin panel statistics.
Implemented user registration blacklist by country.
Reworked the admin panel footer (added language switcher + theme switcher).
Reworked the footer of the whole app.
Reworked the plugin system so plugins won't lose their state anymore when updating.
Improved UI for all tables on mobile.
Improved UX workflow bug when skipping trial & introducing billing details.
Improved responsiveness for account payments & logs pages.
Improved color contrast in Dark mode.
Fixed UI alignment issues on mobile.
Fixed payment generation bug when using discount codes in some cases.
Fixed admin panel settings UI menu bug.
Fixed & improved many other small UI issues.
Update 11.0.0 - 2 January, 2022

Implemented a built-in Contact form page (can be enabled from the admin panel -> website settings -> email notifications).
Implemented the ability to skip a trial when paying for a plan.
Implemented the ability to block registrations from a particular email domain, from the admin panel.
Implemented the ability to purge the cache from the admin panel.
Implemented the ability to set the default data order (asc, desc) the admin panel.
Implemented the ability to set the default pagination results the admin panel.
Implemented the ability to set a custom 404 page from the admin panel.
Implemented the ability to also export to PDF/print data from tables in the admin panel.
Implemented the ability to set custom css and js from the admin panel, for status pages only.
Admin Codes - Implemented the ability to paginate, filter, export data.
Admin Taxes - Implemented the ability to paginate, filter, export data.
Improved the admin panel -> website settings -> main fields, separated them for more clarity.
Improved the file upload error handling.
Improved the UX of impersonating a user, as an admin.
Now reCaptcha and hCaptcha will follow the language that the user currently uses.
Other small yet many improvements of the whole system.
Fixed a few bugs related to the system.
Update 10.0.0 - 17 November, 2021

Implemented PayU one-time payments system.
Implemented Yookassa one-time payments system.
Reworked the admin panel announcements system.
Implemented RazorPay one-time & recurring payments system.
Implemented Mollie one-time & recurring payments system.
Implemented Paystack one-time & recurring payments system.
Implemented an Auto Cleanup functionality for old, inactive users. Can be activated and configured in the admin panel.
Implemented email notifications for old & soon-to-be-deleted users, if the Auto Cleanup functionality is enabled.
Implemented the ability to see the list of referred users of a particular user from the admin panel.
Reworked & improved the API documentation page.
Other bugfixes & improvements.
Update 9.0.0 - 18 October, 2021

Improved the invoices system, now the invoices are immutable.
Reworked the Redeemable Codes system. Redeeming is happening now only from the Checkout page.
Discount/Redeemable codes can now be applied on a per plan basis (more flexibility).
Reworked parts of how the taxes system is working in the admin panel.
All the data tables are now ordered by the date, descending (previous ascending).
Many other code cleanups, improvements and bugfixes.
Update 8.0.0 - 11 September, 2021

Implemented Coinbase (crypto) payments.
Fully reworked the Trial system. Now you can set how many days you want to give out on a per-plan basis.
Implemented the ability to display, edit and set a Custom plan on the plans section, via the admin panel.
Implemented the ability to highlight a particular plan with a particular color via the admin panel.
Implemented Twitter login.
Fully reworked the social logins workflow for better performance and user experience.
Reworked the admin panel plan update, create & user update pages for consistency purposes.
Improved the way admin panel plans are displayed.
If you now redeem a plan that you already have on your account, the redeemed plan days will be now added on top.
Many code cleanups, improvements and other small bugfixes.
Update 7.1.0 - 18 August, 2021

Implemented the ability to enable/disable search engine indexing from the admin panel.
Fully reworked the whole admin panel - website settings page, which now avoids some small, yet annoying bugs & UX bugs.
Reworked the admin panel - pages part for a better UX experience.
Fixed heatmap issue not being displayed properly in some cases.
Update 7.0.0 - 1 August, 2021

Implemented admin panel bulk deletion feature for Websites.
Implemented Google login functionality.
Completely remade the PayPal One Time payments with the new V2 API.
Completely remade the PayPal Subscription payments which fixed a few small UX issues.
Implemented the ability to view & delete all the user logs from the Admin Panel, filter them, export them via CSV and JSON.
Implemented user logs device type, country and operating system tracking for important activities of an account.
Implemented the ability to view all the used coupons of a particular user from the admin panel.
Implemented the ability to export Account Payments to JSON and CSV.
Implemented the ability to export Account Logs to JSON and CSV & filter them.
Improved the consistency of the success messages across the platform, while reducing the size of the translation file.
Reworked the ability to send SMTP test emails from the admin panel for testing.
Fixed small taxes calculation issue.
Fixed small other issues.
Update 6.3.0 - 16 July, 2021

Implemented RTL support.
Implemented the ability to enable/disable the Referral system per plan from the admin panel.
Implemented caching for Goals & Heatmaps on Pixel requests for better performance.
Reworked the way tracking data is sent back to the server for a more efficient way, which also fixed goals not triggering in some cases.
Upgraded the open-source session recording & replay technology to the latest released version 1.0.1.
Fixed & improved various miscellaneous things in the product.
Update 6.2.0 - 17 June, 2021

Implemented email reminders for accounts that are on one-time payments (not recurring) 3 days before expiration.
Implemented the first "Affiliate" plugin, available to purchase here.
Update 6.1.0 - 11 June, 2021

Implemented the first version of the Plugins Management system.
Implemented the first "Offload" plugin, available to purchase here.
Implemented the ability to change the plans order via the admin panel.
Fixed a few small bugs.
Update 6.0.0 - 27 May, 2021

Implemented the ability to switch between raw html content & wysiwyg editor for the admin panel pages system.
Reworked the checkout flow (better UX) for when the user is required to fill in his billing details.
Implemented admin panel statistics total numbers per selected date range.
Fully reworked the admin panel statistics page and separated them for better performance.
Implemented new admin statistics - lightweight pageviews, heatmaps, goals statistics pages.
Implemented new admin panel users management - bulk selection & deletion feature.
Implemented new admin panel Plans API (Read).
Added the last execution date of the Cron Job in the admin panel.
Improved all the emails that are being sent (activation, password reset..etc) for consistency.
Upgraded the open-source session recording & replay technology to the latest version.
Updated the bootstrap library to the latest stable release of 4.6.
Fixed various small admin panel bugs.
Fixed taxes not being properly displayed on invoices in certain cases.
Update 5.1.0 - 26 April, 2021

Implemented the ability to set a text & background color for announcement messages in the admin panel.
Implemented the ability to upload a custom Opengraph image for the index directly from the admin panel.
Fixed statistics email reports bug.
Fixed admin panel plan creation bug.
Fixed dashboard statistics filtering bug.
Update 5.0.0 - 23 April, 2021

Implemented announcements system from the admin panel where you can set a short text announcements for your users.
Implemented hCaptcha, as a great alternative to Google Recaptcha.
Implemented Websites API (CRUD).
Implemented Websites statistics API (Read).
Implemented Payments API (Read).
Implemented User Logs API (Read).
Implemented Admin API Users List endpoint.
Implemented the ability for the API feature to be enabled/disabled per plan.
Implemented language detection based on the browser in certain cases, where possible.
Fully reworked all the statistics related charts: now they are grouped results by years, months, days & hours based on the selected date range.
Some of the forms were remade, now displaying better error messages based on which field generated that error (in case of one).
Improved UX for the Reset Password, Resend Activation, Lost Password pages.
Separated the language JSON file into 2 of them: one for the regular user, one for the Admin panel. This change was done for better performance & also for the fact that most people do not need to also translate the admin panel.
Replaced the TinyMCE library with a faster, more lightweight one for the admin panel pages system.
Reworked the Admin Dashboard.
Updated all product dependencies to their latest versions, where available.
A ton of other improvements, new features, bug fixes, and code cleanups.
Update 4.2.0 - 25 February, 2021

Implemented the ability to view stats by hours for the Admin Statistics page.
Implemented the ability to select an "All time" date picker range for stats.
Improved admin panel CSV and JSON exports: now data from all the pages will be exported at once.
Improved how the UTMs are presented, now you can click on each UTM source and see the medium and campaign linkage.
Fixed heatmaps & goals issues that were occurring on some website and not triggering properly.
Fixed rare timezone related issues occurring in the dashboard stats.
Fixed heatmaps & goals issues that were occurring on some website and not triggering properly.
Fixed goal creation type selector not working properly in some browsers.
Fixed various problems in the dashboard when using an extra language.
Update 4.1.0 - 1 February, 2021

Implemented the ability for the Admin to export to CSV and JSON the users list.
Implemented the ability for the Admin to export to CSV and JSON the payments list.
Implemented the ability for the Admin to set up Webhook URLs events for new user registrations and user deletions (helpful when you want to automatically sign up emails to a newsletter on registration for example).
Fixed one time login code bug for the Admin API.
Update 4.0.0 - 20 January, 2021

Implemented the new Admin API for the users resource (Create, Read, Update, Delete, One time login).
Implemented a new documentation page for the Admin API.
Implemented the ability to enable/disable the Captcha based on individual pages in the admin panel website settings.
Implemented the ability to set the SMTP sender name from the admin panel.
Fully reworked all the Admin Panel tables (Users, Payments, Websites).
Implemented filtering & ordering system in the Admin Panel tables (Users, Payments, Websites).
Improved the performance of the the Pixel tracking modules, Cron and and Sitemap pages.
Improved the payment page when users are prompted to fill the billing details.
Updated the session recording library to the latest version and improved the performance of storing the recorded data.
Reworked and improved the help documentation.
Added the ability to click on the external links of the referrer pages.
Discount codes can now be created for hidden plans as well.
Discount & redeemable codes can now be shared via a link for better convenience.
The city of the visitor can now be seen in the Visitor details page and in the Session replay page.
Fixed Paypal payments problem when a discount is set and the payment is a subscription.
Fixed bug when deleting users from the admin panel and when trying to delete your own account.
Multiple other small fixes, code cleanups and improvements.
Update 3.1.0 - 6 December, 2020

Implemented the ability to set the default theme style (light/dark) from the admin panel.
Implemented a filtering feature for the Account Payments page.
Implemented a filtering feature for the Websites page.
Implemented the Facebook register button on the Register page as well.
Fixed potential timezone problems throughout the product.
Other small fixes and code cleanups.
Update 3.0.0 - 25 November, 2020

Implemented the Lightweight mode of tracking.
< 6 kB tracking script.
Lightweight and performant way of tracking.
No tracking consent needed & fully compliant with GDPR, CCPA, PECR.
Implemented Cities tracking.
Improved performance of the website when a user is logged in.
Improved performance of the Pixel tracking script.
Implemented htaccess browser caching rules for images, css and javascript.
Reworked the app dashboard and other pages for a better user experience, looks and consistency.
Fully removed and replaced the previous datepicker with a better one.
Fully replaced the browser tracking library with a new and more up to date one for better accuracy on link statistics.
Upgraded the open-source session recording & replay technology to the latest version.
From now on, bots will be automatically excluded from being tracked.
Fixed email not being changed when updating it in some cases from the Account settings page.
Fix invoices where inclusive taxes were not calculated properly.
Fix pages created from the admin panel not being ordered properly.
Fix realtime analytics not taking into consideration the timezone of the user.
Update 2.0.0 - 24 September, 2020

Fully reworked & redesigned the checkout process.
Implemented the ability to block bots & crawlers from being tracked.
Implemented the ability to have custom Invoice number prefix.
Implemented the ability to view invoices for all the payments via the admin panel.
Implemented the ability to delete payment logs from the admin panel.
Implemented the ability for admins to create & configure taxes from the admin panel.
Implemented the ability to attach different taxes for any paid plan.
Implemented the ability to enable / disable the taxes & billing system completely from the admin panel.
Implemented email verification when an already existing account is changing their email address to another one for better security.
Updated Stripe payment handler to support the latest API version of Stripe.
Updated Stripe PHP SDK to the latest version.
Updated bootstrap to the latest version 4.5.2.
Updated jquery to the latest version 3.5.1.
Reworked the user account deletion and made it into a new, separated page.
Replaced Google's Favicon provider (for displaying website favicons) with a more privacy-friendly solution from DuckDuckGo.
Replaced country flags api provider with self hosted svg files for countries to avoid being dependant on an API provider.
Fixed Admin User Update not being able to set an account to a disabled status.
A lot of other fixes, code cleanups and improvements that don't need mentioning.
Update 1.4.1 - 7 August, 2020

Implemented the ability for the user to invite a team member to the system, even if the system has the global registration disabled.
Implemented the ability to switch Teams creation access via Plans (from the admin panel).
Fixed admin plan update not properly working when clicking on update all subscribers button.
Fixed admin dashboard when the payment system is not enabled for regular license holders, in some cases.
Fixed small cron job related problem.
Update 1.4.0 - 4 August, 2020

Implemented the ability to offer Lifetime deals to your customers.
Implemented the ability to turn off certain Payment Frequencies per Plan (from the admin panel)
Implemented a dedicated "Thank you" page after a successful payment with access to payment-related data from javascript to also make external affiliate tracking much more easy to implement.
Implemented the ability to take on Offline payments.
Implemented pagination for the Account Payments and Account Logs pages.
Reworked the Admin Panel User View page to show more details and have direct links to users related content.
Reworked the Admin Panel Plan Update page to have a more clearly defined actions when updating a plan.
Improved Admin Codes, Pages, Pages Categories to show a more beautiful default view when no codes are created.
Improved the Admin Panel Dashboard responsiveness and widgets for mobile.
Improved a lot of other parts in the Admin panel to be more user friendly.
Reworked how the Dark / Light switcher is working.
Reworked parts of the Packages choosing page, Payment checkout page and improved them.
Improved the speed of execution of the following pages: Sitemap, Generation of the simple captcha, Stripe & Paypal Webhooks.
Fixed Facebook login not tracking the Country of the user on registration.
Fixed Cron Job problem that would not delete old session replays from the storage folder.
Fix potential bug in the visitors page where it would not display the css in some cases.
Fixed goals and heatmaps sometimes not being triggered if the website is introduced without www. in 66analytics and in the actual live website, it is accessed via www.
Fixed pixel code not properly tracking single page type apps properly.
Upgraded phpmailer, recaptcha, stripe, fontawesome libraries to the latest versions.
Upgraded open source library responsible for generating the heatmaps and session recordings.
Ads which are set from the admin panel will now not show on the Login, Register, Lost password, Resend activation and Reset Password, Plan selection, Payment and Thank you payment pages.
Removed 50% of the size of the FontAwesome library by only using the needed fontawesome brand icons (~600 kB saving).
Various other code cleanup, improvements and looks improvement throughout the product.
Update 1.3.1 - 18 June, 2020

Improved the way the Dashboard is displayed when trying to use the Print function and also added a quick Export to PDF button.
Improved the way Team invitations are sent so that the user will get different mails with different links based on the fact if the invited user already has an account or needs to register a new one.
Improved responsiveness in the visitor details page, especially on mobile devices.
Improved the way the Pixel is recognizing domains and will now automatically look for either "www.domain.com" or "domain.com".
Improved the visual presentation on the Admin Page Create & Update and Admin Page Category Create & Update.
The JavaScript pixel code will now stop loading the Heatmaps & Recording scripts if the tracked website does not use these functions, in order to decrease the size about 50%.
Fixed problem with invited Team members that could not access the teams page or see any statistics without an active Plan.
Fixed Admin Page Update problem not deleting the cache after the update.
Fixed Replays page error when applying certain filters.
Fixed Reset Password function not resetting the 2FA token as well. Now it will completely remove the set 2FA Token when resetting the password.
Fixed goals update and deletion bug.
Fixed Heatmaps and Goals limit not properly working when setting to -1 (unlimited).
Other minor improvements and fixes.
Update 1.3.0 - 31 May, 2020

Implemented Goals tracking.
Implemented a way to track Goals as pageview events.
Implemented a way to track Custom Goals via a JavaScript snippet code.
Implemented the ability for the admin to specify if a user has access to the Goal Tracking functionality and to limit it.
Implemented Email Reports.
Implemented the ability for the admin to fully enable or disable this functionality.
Implemented the ability for the admin to specify if a user has access to the Email Reports functionality.
Implemented the ability for the user to specifically enable or disable email reports for each tracked website individually.
Fully reworked the Admin Statistics page with a new structure and more statistics.
Fully redesigned the Admin Panel.
Implemented pagination for the Websites list page.
Implemented the ability to see the list of all the accessed pages links from a Session replay when clicking on the number of Events a Replay has, while inside of the Replay page.
Session recording will now do not track any email, tel types of fields and also any field which might have other personal details (names, phone numbers, addresses, credit cards..etc).
The "Track Visitors Events" function will now do not collect any form fields, only the fact that a form has been submitted.
Reworked the way Scrolling events are tracked so that it will track the scrolling percentage and not the pixels.
Reworked the Heatmaps, Replays, Visitors page pagination to not use DataTables anymore.
Added more data to the Help page regarding Privacy and how to use Custom Goals Tracking.
Fixed Paypal Recurring Annual payments bug.
Fixed Admin User Create function not taking into consideration the default timezone and language when creating the user.
Fixed Admin Settings page being slow in certain cases when saving data.
Multiple other fixes and improvements.
Update 1.2.0 - 8 May, 2020

Implemented Dark mode.
Implemented Two-factor authentication option for users.
Implemented Bounce rates for Top pages and Referrers widgets.
Implemented Exit Pages statistics to see which are the pages where people leave off your website in most times.
Implemented the ability to click on the Referrer domain and see which pages from that domain were the referrers.
Implemented new a way of updating the database, automatically via a web interface (instead of running SQL queries manually).
Implemented the ability to hide Plans from the admin panel while still having them active.
Improved the Pixel loading and Pixel Tracking script performance by avoiding unnecesarry calls to the database.
Improved the way Sessions are replayed and fixed problems which caused the session replay page to fail loading when the replay data is bigger than normal.
Improved the way Heatmaps are displayed and fixed problems which caused the heatmap page to fail loading when the heatmap data is bigger than normal.
Reworked the installation process and documentation pages design to a much cleaner one and to resemble the new logo of the AltumCode brand.
Reworked the storage of the Session replays to a new folder to better differentiate it (as previously it was in the same folder with that cache).
Fixed potential problems with Stripe recurring payments.
Fixed heatmaps generation problems in some situations.
Fixed potential problems with Paypal payments when using coupons.
Fixed datepicker input not showing up on certain mobile phones.
Fixed CronJob not properly cleaning up certain stuff.
Other minor fixes and improvements.
Update 1.1.3 - 22 March, 2020

Improved performance for logged in users by reducing the amount of calls to the database.
Improved performance of the overall website usage by using a caching system to avoid unnecessary calls to the database.
Fully reworked how the Sessions Replays are stored and processed and highly improved reading and writing performance as well. Now instead of storing all the big chunks of data in the database, they will be store on the server files
Fully reworked how the Sessions Replays limits are taken into consideration. Now you will be able to set how many total session replays a user can have, instead of total events (which was pretty ambigous).
Implemented the ability to limit the time duration (in minutes) of replays. It can be done from the admin panel, per plan or per user so that you limit the amount of data the website collects.
Implemented the ability to set Excluded IPs per website if you do not want to be tracked.
Implemented the ability to set the Cache expiration time for the Pixel code. Feature meant for advanced users, leave it default to 600 for optimum performance.
Other overall improvements of the whole system.
The pixel code will not output notices in the console if the tracking is disabled by either Opting out or the user having DNT enabled.
Removed filter for the field "name" in the Registration page so that users can use utf8 characters as well.
Fixed bug on Stripe payments higher than 999.
Fixed heatmap page problem, not being able to use the dropdown actions.
Fixed heatmaps not being able to be accessed by team members.
Fixed dashboard graph not properly showing in some timezones.
Update 1.1.2 - 3 March, 2020

Implemented a new 'Verify Pixel' modal when getting the Tracking code for a website so that users can easily confirm they installed the pixel code correctly.
Implemented a new field for each user named 'Country', which will be detected based on the last login of the user.
Reworked the way the CronJob cleans up the system to a more performant versions.
Reworked the whole multi-language system to improve the quality of the site and have proper SEO when having multiple languages at the same time.
Updated the GeoLite countries database and the MaxMind reader to the latest version (Country detection).
Fixed Date Selectors not working properly in some Timezones.
Fixed heatmaps not working in some scenarios.
Update 1.1.1 - 21 February, 2020

Implemented the ability to disable an user account from the Admin User Update page.
Improved consistency of icons width displayment for all pages.
Improved heatmap displayment on top of the page, made it more transparent so you can see a bit of the page.
Fixed bug where the Snapshot of a Heatmap will not create if sessions replays are active on a specific website.
Fixed cron job not resetting the user's websites session replays usage.
Fixed footer social link not disappearing if no value is inserted in the admin panel.
Update 1.1.0 - 14 February, 2020

Implemented new Heatmaps for clicks functionality.
New Heatmaps page where you can see all the created heatmaps and you have the ability to create a new heatmap.
New Heatmap page where you can check the actual heatmap out.
Implemented the ability to have 3 different snapshots per heatmap for Desktop, Tablet & Mobile screens at the same time.
Implemented the ability to reset snapshots for heatmaps.
Implemented the ability to turn on/off the Heatmaps functionality from the admin panel.
Implemented the ability for the admin to specify how many heatmaps a Plan/User can create.
Implemented average time per session to display in the visitors and visitor page.
Implemented a new option in the admin panel which will automatically clean Session Replays which do not meet a certain amount of seconds in activity.
Implemented filters for visitors on the Visitors page.
Implemented filters for visitors on the Replays page.
Implemented a 5 minute cache for the Pixel code to avoid making unnecessary calls to the server
Improved the header of the Replays / Visitors page.
Improved the look of the dashboard and other pages of the app.
Improved mobile responsiveness throughout the product where it was lacking.
Fixed some date/timezone related problems in the system and made them more consistent.
Fixed being able to create 100% discount codes. Use redeemable instead when trying to create a redeemable package for free.
Fixed the delete replays button deleting all the replays and not taking into consideration the date filter. Now the delete replays function will delete only replays from the selected date range and applied filters.
Fixed various visual bugs.
Update 1.0.1 - 28 January, 2020

Implemented pages categories.
Reworked and improved the pages system.
Implemented "Resources center" where you can see the most popular pages and categories for all the pages.
Implemented the ability to delete Sessions replays from a specific date range for easier clearing.
Paypal recurring system refactored, now it will accept the first payment instantly without any delay.
Fixed notice in Pay page when trying to pay via Stripe.
Now the options to event track and session replay are disabled if the user doesnt have access to them.
Initial release - 19 January, 2020

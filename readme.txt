=== SMTP ===
Contributors: hel.io, qrawl
Donate link: http://hel.io/donate/
Tags: smtp, email, mail, wp_mail, mailer, phpmailer
Requires at least: 3.0
Tested up to: 3.9.1
Stable tag: 1.2

Allows you to configure and use a SMTP server (such as Gmail) for sending emails.

== Description ==

This plugin configures WordPress to use a SMTP server when sending emails instead of the default PHP `mail()` function.

It also creates a settings page where you can enter the SMTP server details and authenticatin credentials if needed.

== Installation ==

1. Upload the plugin to the `/wp-contents/plugins/` folder.
2. Activate the plugin from the 'Plugins' menu in WordPress.
3. Configure the SMTP details from the 'SMTP' settings page

== Frequently Asked Questions ==

= Will the plugin work with versions prior to 3.0? =

I have not tested the plugin with a WordPress version lower than 3.0 so it might or it might not work. You can give it a try.

= I have a plugin that sends out emails but doesn't use SMTP. Why? =

Said plugin has to use the WordPress default `wp_mail()` function when sending emails in order for SMTP to work.

= How do I set up the plugin to use the Gmail SMTP? =

Use the following settings:

Host: smtp.gmail.com
Port: 465
Encryption: SSL
Username: gmail address
Password: gmail password

== Screenshots ==

1. Screenshot of the SMTP settings page.

== Changelog ==

= 1.2 =
* Sender's name and address are now the blog name and the admin email
* More consistent form input types in settings page
* Italian translation
* Updated compatibility tag to Wordpress 3.9.1

= 1.1 =
* The password field is of type password instead of text and does not display your saved password 
* Now storing encrypted passwords in the database (Make sure you re-enter your password if you are updating)

= 1.0 =
* Initial release.

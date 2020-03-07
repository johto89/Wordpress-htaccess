# Wordpress-htaccess
Secure Wordpress using htaccess

Change google.com or https://www.google.com.vn/ to your domain


# Block access to wp-admin.
<Files wp-login.php>
Order deny,allow
Deny from all

Allow from 8.8.8.8 ======> The IP address used to access wp-admin
</Files>

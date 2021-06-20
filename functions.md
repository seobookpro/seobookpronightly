# Change the default Upload Media Path in WordPress wp-config.php
Add the snippet code below

To Change the WordPress Default Media Upload Path add define( 'UPLOADS', ''.'media' ); Right after the define( 'WP_DEBUG', false );
You Need to Have this directory in your public_html/ root folder as new folder with 755 Premissions Otherwise on the first upload the folder named below will be created as new


define( 'WP_DEBUG', false );
define( 'UPLOADS', ''.'media' );
/* That's all, stop editing! Happy publishing. */



## Submit Your Theme the WordPress Directory
### Make WordPress Themes

Submit Your Theme or Theme Update to the Directory

Your theme will be submitted for review to be distributed on the official WordPress.org Theme Directory.
Read the requirements before updating a theme

In order to have your theme hosted on WordPress.org, your code is required to comply with all the requirements on the Theme Review Teams handbook page.

https://wordpress.org/themes/upload/



SOCIOKAIROS Website - IONOS Deployment Guide
=============================================

1.  Extract this ZIP file on your computer.

2.  Log in to your IONOS hosting control panel:
    https://login.ionos.com/

3.  Go to Hosting > Your Domain > File Manager
    (or use FTP with your favorite client).

4.  Upload ALL files and folders to the root directory
    (usually / or /public_html/):

    index.html          -> Main entry point
    404.html            -> Redirects to index for SPA routing
    .htaccess           -> Server configuration (routing, caching, security)
    assets/             -> JavaScript and CSS bundles
    images/             -> All images (logo, photos, screenshots)
    videos/             -> Video files

5.  Make sure the .htaccess file is uploaded (it may be hidden
    in your file manager - enable "Show hidden files").

6.  Visit your domain - the website should be live!

IMPORTANT NOTES:
- Do NOT rename or move any files/folders.
- The .htaccess file is required for page routing to work.
- If you get 404 errors, ensure mod_rewrite is enabled on your hosting.

For support: contacto@sociokairos.com

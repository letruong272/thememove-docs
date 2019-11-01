# Theme Requirements

To use Freshen, you must be running **WordPress 4.9 or higher, PHP 5.4 or higher, and MySQL 5 or higher**. We have tested it with Mac, Windows and Linux. Below is a list of items you should ensure your host can comply with.

- Check to ensure that your web host has the minimum requirements to run WordPress.
- Always make sure they are running the latest version of WordPress.
- You can download the latest release of WordPress from official WordPress website.
- Always create secure passwords for FTP and Database.

Hosting is more secure when PHP applications, like WordPress, are running using your account’s username instead of the server’s default shared username (www or www-data). The most common way for hosting companies to do this is using PHP. Just ask your potential host if they run PHP or something similar.

## Recommended PHP Configuration Limits

Many issues that you may run into such as: white screen, demo content fails when importing, empty page content and other similar issues are all related to low PHP configuration limits.\
The solution is to increase the PHP limits. You can do this on your own, or contact your web host and ask them to increase those limits to a minimum as follows:

```
max_execution_time 300
memory_limit 256M
post_max_size 32M
upload_max_filesize 32M
```

You can verify your PHP configuration limits in the System tab in the Backend-mainpage. Take a look in the left sidebar for **WordPress backend > ThemeMove Core > Tools > System Info**.

![system-info](images/system-info.png)

> You should submit the system info when submitting a support ticket, by clicking on the blue button **Download System Info File**
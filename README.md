# [MageVision](https://www.magevision.com/) Admin Category Product Link Extension for Magento 2

## Overview
The Admin Category Product Link extension is a simple but really useful extension which gives you the ability to edit products directly from the category products tab in Magento admin. In the category products tab you can see all products currently assigned to that category, but there is no quick way to navigate to a product for editing. So the extension adds a product edit link for every product in category products tab. Save time by editing the product directly from a category instead of having to navigate through products grid and search for that product to edit.

## Key Features
	* Direct product edit link in category products tab
	* Save Time
	
## Other Features
	* Developed by a Magento Certified Developer
	* Meets Magento standard development practices
	* Simple installation
	* 100% open source

## Compatibility
Magento Community Edition 2.4

## Installing the Extension using an archive and FTP
	* Backup your web directory and store database
	* Download the extension
		1. Sign in to your account
		2. Navigate to menu My Account → My Downloads
		3. Find the extension and click to download it
	* Extract the downloaded ZIP file in a temporary directory
	* Upload the extracted folders and files of the extension to base (root) Magento directory. Do not replace the whole folders, but merge them. If you have downloaded the extension from Magento Marketplace, then create the following folder path app/code/MageVision/AdminCategoryProductLink and upload there the extracted folders and files.
        * Connect via SSH to your Magento server as, or switch to, the Magento file system owner and run the following commands from the (root) Magento directory:
            1. cd path_to_the_magento_root_directory 
            2. php bin/magento maintenance:enable
            3. php bin/magento module:enable MageVision_AdminCategoryProductLink --clear-static-content
            4. php bin/magento setup:upgrade
            5. php bin/magento setup:di:compile
            6. php bin/magento setup:static-content:deploy
            7. php bin/magento maintenance:disable
        * Log out from Magento admin and log in again

## Installing the Extension via composer
	* Backup your web directory and store database
    * Connect via SSH to your Magento server as, or switch to, the Magento file system owner and run the following commands from the (root) Magento directory:
        1. cd path_to_the_magento_root_directory 
        2. php bin/magento maintenance:enable
        3. composer require magevision/module-admin-category-product-link
        4. php bin/magento module:enable MageVision_AdminCategoryProductLink --clear-static-content
        5. php bin/magento setup:upgrade
        6. php bin/magento setup:di:compile
        7. php bin/magento setup:static-content:deploy
        8. php bin/magento maintenance:disable

## Support
If you need support or have any questions directly related to a [MageVision](https://www.magevision.com/) extension, please contact us at [support@magevision.com](mailto:support@magevision.com)

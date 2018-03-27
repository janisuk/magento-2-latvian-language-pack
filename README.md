## Magento 2 Latvian Language Pack

**Magento 2 Latvian Language Pack** will show you a simple way to interpret the default language into Latvian on the Magento 2 stores. The Latvian Language Package, the in-line translation guide, is the fastest way to translate mass localization files instead of having to locate the strings before. The data comes from translation project at Crowdin, then automatically all are delivered to the Latvian language. To install the language package on the store, please keep your eyes on this topic.

Read more [Magento 2 Latvian Language Pack](https://www.mageplaza.com/magento-2-latvian-language-pack.html)


## Overview

- Download & Contribute
- Install Latvian Language Pack
- How to Install Latvian Language Pack

## 1. Download & Contribute to Latvian Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Latvian Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-latvian-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-latvian-language-pack/tarball/master)


Find other [language packs here](https://www.mageplaza.com/kb/magento-2-language-pack/)

## 2. How to Install Latvian Language Pack

There are 3 different methods to install this language pack.

### ✓ Method #1. Composer method (Recommend)
Install the Latvian language pack via composer is never easier.

**Install Latvian pack**:

```
composer require mageplaza/magento-2-latvian-language-pack:dev-master
php bin/magento setup:static-content:deploy lv_LV
php bin/magento cache:flush

```


**Update  Latvian pack**:

```
composer update mageplaza/magento-2-latvian-language-pack:dev-master
php bin/magento setup:static-content:deploy lv_LV
php bin/magento cache:flush

```

#### Authentication required (If any)

![Authentication required](https://cdn.mageplaza.com/media/general/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### ✓ Method #2. Copy & Paste method (Not recommended)

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Latvian language pack
- Step 2: Unzip Latvian pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Latvian language pack

You can download the language pack from above link

#### Step 2: Unzip Latvian pack

Unzip the Latvian language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip app/code/Mageplaza/lv_lv
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### ✓ Method #3. Download and install manually (Not recommended)

To download and install Latvian pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-latvian-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-latvian-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `lv_LV.zip` into `app/i18n/mageplaza/lv_LV/lv_LV.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## 3. How to active Latvian language pack

Now time to active the Latvian language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Latvian language pack}}](https://cdn.mageplaza.com/media/general/aPSUA0l.png)


## 4. How to contribute
<!-- ![process](http://progressed.io/bar/80) -->

Contribute to this language at https://crowdin.com/project/magento-2/lv

## Supported Magento versions

- Magento v2.0.x
- Magento v2.1.x
- Magento v2.2.x



## Note

- This project automatically updates weekly from Crowdin.
- Any question, issue please [create a new issue](https://github.com/mageplaza/magento-2-latvian-language-pack/issues/new)

## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


## References:

- https://www.mageplaza.com/magento-2-latvian-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/
- https://crowdin.com/project/magento-2








## Mageplaza extensions on Magento Marketplace, Github



☞ [Blog](https://github.com/mageplaza/magento-2-blog)

☞ [Social Login](https://github.com/mageplaza/magento-2-social-login)

☞ [SEO](https://github.com/mageplaza/magento-2-seo)

☞ [SMTP](https://github.com/mageplaza/magento-2-smtp)

☞ [Product Sliderthub](https://github.com/mageplaza/magento-2-product-slider)

☞ [Banner](https://github.com/mageplaza/magento-2-banner-slider)

☞ [Sample Payment Method](https://github.com/mageplaza/magento-2-sample-payment-method)




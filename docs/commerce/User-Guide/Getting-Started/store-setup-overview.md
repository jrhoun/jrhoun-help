# Store Setup Overview

## Introduction

This article is intended to provide a walk through for users who are new to building a store in Liferay Commerce. It assumes that Liferay Commerce (and Liferay DXP) have been appropriately installed and configured. For more information on installation, see the [Installation Overview](../../../installation-and-upgrades/installation-guide/installation-overview/README.md).

## Road Map

* [Store Setup](#store-setup)
* [Creating the Storefront](#creating-the-storefront)
* [Managing Customer Accounts](#managing-customer-accounts)
* [Managing Orders and Shipments](#managing-orders-and-shipments)

## Store Setup

> **Note**: An [Accelerator](../../getting-started/accelerators/README.md) may be used to create the store site. Using an Accelerator to create the store site will configure many of the settings mentioned in this section, see [Using the Minium Accelerator to Jump Start Your B2B Store](../../getting-started/accelerators/using-the-minium-accelerator-to-jump-start-your-b2b-store/README.md) for further details.

Initial store setup is done with the [Admin account](../introduction-to-the-admin-account/README.md). Read the [Liferay Commerce Configuration Overview](../liferay-commerce-configuration-overview/README.md) to become more familiar with the Liferay Commerce configuration layout and available options.

### Configure Global Commerce Settings

Global configurations for Liferay Commerce include setting the store timezone, available languages, adding regions and region specific measurement units, and more. Learn more from the following articles:

* [Setting Locale Options](../locale-options/README.md)
* [Adding Regions](../country-options/adding-regions/README.md)
* [Setting up Warehouses](../../catalog/managing-inventory/warehouse-reference-guide/README.md)
* [Creating Channels](../../catalog/creating-and-managing-products/channels/introduction-to-channels/README.md)

### Create a Store Site

Liferay Commerce supports B2B, B2C, and B2C-B2B stores. [Site Types](../site-management-basics/sites-and-site-types/README.md) designate a store's business model and will determine how the storefront works with Accounts.

Liferay Commerce is built on Liferay DXP; For more information about how Liferay DXP Sites work, see [Building a Site](https://help.liferay.com/hc/en-us/articles/360018171231-Building-a-Site).

### Configure Store Site Commerce Settings

The following sections cover configurations that are store site specific.

#### Accepting Payment

Liferay Commerce provides support for several third party payment processors and also allows for the use of money orders to accept payment. See:

* [Payments](../payments/README.md)
* [Managing Payment Methods](../payments/managing-payment-methods/README.md)
* [Authorize.net](../../sales/payments/payment-methods/authorize.net/README.md)
* [PayPal](../../sales/payments/payment-methods/paypal/README.md)
* [Mercanet](../../sales/payments/payment-methods/mercanet/README.md)
* [Money Orders](../../sales/payments/payment-methods/money-orders/README.md)

#### Collecting Applicable Taxes

In order to collect the applicable taxes, Liferay Commerce has the ability to create tax categories and to set tax rates by address or by a fixed rate.

* [Creating Tax Categories](../../operations/taxes/creating-tax-categories/README.md)
* [Setting Tax Rate by Address](../../operations/taxes/setting-tax-rate-by-address/README.md)
* [Setting Tax Rate by Fixed Rate](../../operations/taxes/setting-tax-rate-by-fixed-rate/README.md)

#### Shipping Products

Liferay Commerce has several options to calculate shipping rates. Commerce Enterprise subscribers receive FedEx carrier integration out-of-the-box.

* [Shipping Methods](../shipping-methods/README.md)
* [Variable Rate](../../sales/shipping/using-the-variable-rate-shipping-method/README.md)
* [Flat Rate](../../sales/shipping/using-the-flat-rate/shipping-method/README.md)
* [Using FedEx as a Carrier](../../sales/shipping/using-fedex-as-a-carrier-method/README.md)

## Creating the Catalog

After setting up the store, begin [creating a catalog](../../catalog/creating-a-catalog/README.md).

### Adding Products to a Catalog

When adding a product, there are three product types: **Simple**, **Grouped**, and **Virtual**. See the [Introduction to Product Types](../../catalog/creating-and-managing-products/product-types/introduction-to-product-types/README.md) for more information.

#### Adding Product Information

The Liferay Commerce Catalog supports storing and managing a wide variety of product information. The following articles cover some of the available options:

* [Product Options](../../catalog/creating-and-managing-products/customizing-your-product-with-product-options)
* [Product Specifications](../../catalog/creating-and-managing-products/product-information/specifications/README.md)
* [Product Images](../../catalog/creating-and-managing-products/product-information/product-images/README.md)
* Product Attachments
* [Product Relations](../../catalog/creating-and-managing-products/product-information/related-products-up-sells-and-cross-sells/README.md)
* [Product Categorization](../../catalog/creating-and-managing-products/categories/organizing-your-catalog-with-product-categories/README.md)
* [Availability Estimates](../../catalog/managing-inventory/availability-estimates/README.md)
* [Low Stock Activity](../../catalog/managing-inventory/low-stock-activity/README.md)
* Applicable Tax Category
* Associated Channels
* Associated Account Groups
* BOM / Spare Parts

#### Product Pricing

There are several ways to price products and these methods are related to one another in a pricing hierarchy: base price, price list, tiered price, promo price and discount. Pricing is managed per SKU.

* [Pricing](../../catalog/managing-price/introduction-to-product-pricing-methods/README.md)
* [Price Lists](../../catalog/managing-price/price-lists/creating-a-price-list/README.md)
* [Discounts](../../marketing/promotions/adding-discounts-by-product/README.md)

#### Managing Inventory

* [Introduction to Managing Inventory](../../catalog/managing-inventory/introduction-to-managing-inventory/README.md)
* Subscriptions (if applicable)

## Creating the Storefront

Building a store in Liferay Commerce requires more than a complete catalog. Store administrators building a storefront from scratch will need to add a series of pages to display and sell their products.

See [Creating Your Storefront](../../content/pages/creating-your-storefront/README.md) to learn more.

## Managing Customer Accounts

To learn more about how accounts, inviting users accounts, account roles, and more, read the following articles:

* [Introduction to Accounts](../../customers/account-management/introduction-to-accounts/README.md)
* [Creating a New Account](../../customers/account-management/creating-a-new-account/README.md)
* [Inviting Users to an Account](../../customers/account-management/inviting-users-to-an-account/README.md)
* [Adding Addresses to an Account](../../customers/account-management/adding-addresses-to-an-account/README.md)
* [Account Roles](../../customers/account-management/account-roles/README.md)
* [Assigning Account Roles](../../customers/account-management/assigning-account-roles/README.md)
* [Creating a New Account Group](../../customers/account-management/creating-a-new-account-group/README.md)

## Managing Orders and Shipments

When an order has been received, the order may be transmitted to an ERP and optionally to a CRM. Once the requested goods are available for shipping, the store's inventory specialists may track the shipment. See the following articles to learn about the life cycle of an order and the shipment processes.

* [Order Life Cycle](../../sales/order-management/order-life-cycle/README.md)
* [Introduction to Shipments](../../sales/order-management/managing-shipments/introduction-to-shipments/README.md)
* [Creating a shipment](../../sales/order-management/managing-shipments/creating-a-shipment/README.md)
* [Cancelling a Shipment](../../sales/order-management/managing-shipments/cancelling-a-shipment/README.md)
* Shipping Override

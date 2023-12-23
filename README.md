

# Next Generation Front-End for WooCommerce



## Introduction

The goal of Nuxt is to provide a modern, fast, and SEO friendly front-end for WooCommerce. It's built on top of Nuxt 3 and uses the WPGraphQL API to retrieve all the data it needs. It's also fully customizable and can be extended with your own components and modules. You can see a live demo of WooNuxt by clicking the button below.



&nbsp;

## Get Started

- Download the plugin.
- Install and activate the plugin on your WordPress site. This will install all the required plugins for Nuxt, add some useful fields to the WPGraphQL schema, and automatically retrieve the WooCommerce payment gateway settings for Stripe and PayPal.
- Once the plugin is activated your ready to deploy WooNuxt on a whatever hosting you like, or click one onf the fast deploy button below.
- Once the plugin is activated the only required environment variable is `GQL_HOST`. Checkout the .env.example file for more details.



&nbsp;

### Progress

| Feature                                               | Ongoing Enhancements | Done | In Progress | In the Pipeline |
| ----------------------------------------------------- | -------------------- | ---- | ----------- | --------------- |
| Proformanance                                         | ✅                   | ✅   |             |                 |
| SEO                                                   |                      |      | ✅          |                 |
| Cart                                                  |                      | ✅   |             |                 |
| Search                                                |                      | ✅   |             |                 |
| Shipping                                              |                      | ✅   |             |                 |
| Checkout (Stripe, PayPay, Cash on Delivery)           |                      | ✅   |             |                 |
| Filtering                                             | ✅                   | ✅   |             |                 |
| Wishlists                                             |                      | ✅   |             |                 |
| Account                                               |                      |      | ✅          |                 |
| Coupons                                               |                      | ✅   |             |                 |
| Product Reviews                                       |                      |      | ✅          |                 |
| Product Category Pages                                |                      |      | ✅          |                 |
| WooNuxt Settings Module                               |                      |      | ✅          |                 |
| Better Typescript Supp                                |                      |      | ✅          |                 |
| Mobile layout                                         | ✅                   |      | ✅          |                 |
| Countries & States Enums                              |                      |      |             | ✅              |
| Cookie Popup & GDPR Compliance                        |                      |      |             | ✅              |
| Progressive Web App (PWA)                             |                      |      | ✅          |                 |
| Queing System (for chcecking out when server is busy) |                      |      |             | ✅              |
| Language Support (i18n)                               |                      |      | ✅          |                 |

&nbsp;

### Required WordPress Plugins

| Plugin Name    | Description                              | Link                                        |
| -------------- | ---------------------------------------- | ------------------------------------------- |
| WPGraphQL      | A free, open-source plugin for WordPress | https://www.wpgraphql.com/                  |
| WooGraphQL     | GraphQL API for WooCommerce              | https://woographql.com/                     |
| WPGraphQL Cors | Enable CORS for WPGraphQL                | https://github.com/funkhaus/wp-graphql-cors |

> **Note** The the [WooNuxt Settings]plugin will help you install all the required plugins.

&nbsp;

### Required Environment Variables

`GQL_HOST` - The URL of your WordPress site. This is the only required environment variable.

&nbsp;

#### Tested up to:

| Plugin/Software | Version |
| --------------- | ------- |
| WordPress       | 6.2.0   |
| WooCommerce     | 7.6.0   |
| WPGraphQL       | 1.14.0  |
| WooGraphQL      | 0.12.3  |
| Node            | 16.18.1 |

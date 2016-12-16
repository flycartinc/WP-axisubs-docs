# Paypal

Paypal standard plugin for Axisubs. It allows you to accept payments via Paypal Payment Gateway. This uses the Paypal's Website Standard Payment. Customer will be redirected to Paypal to make payment securely.

## Requirements

```
       1.PHP 5.6 or higher

        2.Wordpress 4.6.1 and above

        3.Axisubs version 1.0.0 or higher
```

## Installation

- Download the package from our site and install it using wordpress plugin installer.

- After installing plugin, go to Axisubs > Apps and click on **Enable** to activate the paypal plugin.

- Once activated, click on **view** to open the plugin and setup the basic configuration.

## Configuration

**Payment title**

Set the name for the paypal option.The text what you have entered in the payment option tittle textbox will appear during billing process.

**Plugin Display Image**

This option will help you to add the image for the paypal option. Image added here will be appeared in payment options list.

**Paypal Email**

Enter the valid Paypal registered emai id of the merchant.

### What is IPN ?

Instant Payment Notification (IPN) is a message service that automatically notifies merchants of events related to PayPal transactions. Merchants can use it to automate back-office and administrative functions, including automatically fulfilling orders and providing customers with order status.

**Validate IPN**

It has 2 boolean option 'yes' or 'no'. Choose **YES** to enable validate IPN.

**Sandbox**

Paypal offers you the sandbox feature. Choose **yes** to enable the sand box and set **no** to disable the sand box.

**Sandbox Email**

Enter the valid sandbox email id of the merchant.

**Debug**

Choose YES to enable the debug mode. If you set this to yes, then debug messages will be logged and saved in the cache folder in your wordpress directory. DO NOT select YES in the live site.

**Payment button text**

Text entered here will be added as the name of the payment button.

**CBT**

Sets the text for the Return to Merchant button on the PayPal Payment Complete page. For Business accounts, the return button displays your business name in place of the word Merchant by default.

**Image**

The URL of the 150x50-pixel image displayed as your logo in the upper left corner of PayPal's checkout pages. Default: your business name (if you have a Business account) or your email address (if you have Premier account).

This is an optional setting.

**Header Background**

Use this option to set the background color for header. The hex-code of your PayPal checkout page's header backgroud, e.g. FFFFFF.

This is an optional setting.

**Header Border**

The 6 digit hex-code to the color for payPal checkout page's header border, e.g. FFFFFF for white. This is an optional setting.

# PaySuper Examples

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-brightgreen.svg)](https://www.gnu.org/licenses/gpl-3.0) 
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/paysuper/paysuper-examples/issues)

It’s easy to embed PaySuper JS SDK with just a few lines of Javascript code to start a payment process and display a purchase status finally without any server-side code.

Learn more about a [payments flow](https://docs.pay.super.com/docs/payments/quick-start) and [PaySuper Checkout integration](https://docs.pay.super.com/docs/payments/sdk-integration).

|   | PaySuper Service Architecture
:---: | :---
✨ | **Checkout integration.** [PaySuper JS SDK](https://github.com/paysuper/paysuper-js-sdk) is designed to integrate a Checkout Form on a merchant's website or a game client.
💵 | **Frontend for a payment form.** [PaySuper Payment Form](https://github.com/paysuper/paysuper-payment-form) is a frontend for a single-page application with a payment form.
📊 | **Frontend for a merchant.** [PaySuper Dashboard](https://github.com/paysuper/paysuper-dashboard) is the BFF server and frontend to interact with all PaySuper related features for merchants.
🔧 | **Payment Form API Backend.** [PaySuper Checkout](https://github.com/paysuper/paysuper-checkout) is a REST API backend for [PaySuper Payment Form](https://github.com/paysuper/paysuper-payment-form) and a billing processing such as purchase receipts and others. Public API methods are documented in the [API Reference](https://docs.pay.super.com/api).
🔧 | **Billing API Backend.** [PaySuper Management API](https://github.com/paysuper/paysuper-management-api) is a REST API backend for [PaySuper Dashboard](https://github.com/paysuper/paysuper-dashboard) and other management API methods. Public API methods are documented in the [API Reference](https://docs.pay.super.com/api).
💳 | **Payment processing.** [PaySuper Billing Server](https://github.com/paysuper/paysuper-billing-server) is a micro-service that provides with any payment processing business logic.

***

## Features

**Conversion-optimized:** The payment form loads instantly with a single-page layout.

**Payment methods:** VISA, Master Card, AMEX, JCB, China UnionPay, Bitcoin payments, Alipay, QIWI, Bank Wire Transfers.

**Payment types:** Simple Checkout, Items Checkout.

**Authentication:** Dynamic 3D Secure (ready for Strong Customer Authentication).

**Localization:** Localized for [24 languages](https://docs.pay.super.com/docs/payments/localization).

## Table of Contents

- [Demo](#demo)
- [Developing](#developing)
- [Samples](#samples)
- [Contributing](#contributing-feature-requests-and-support)
- [License](#license)

## Demo

Try out [the payment sample](https://checkout.pay.super.com/demo/shop) for the [Simple Checkout](https://docs.pay.super.com/docs/payments/#simple-checkout) and [Products Checkout](https://docs.pay.super.com/docs/payments/#products-checkout).

## Developing

The payment form can be embedded as an iframe or modal window.

After payment, a customer will be automatically redirected to [URLs for a successful or failed payment](https://docs.pay.super.com/docs/payments/live/#fill-in-the-redirect-urls).

[Follow these steps for integration](https://docs.pay.super.com/docs/payments/sdk-integration).

## Samples

Samples for a payment initialization for any types of products:

* [Simple Checkout](simple-checkout.html)
* [Game Key Checkout](key-checkout.html)
* [Virtual Item Checkout](item-checkout.html)

Samples for rendering the form:

* [Render as a modal window](modal-checkout.html)
* [Render as an iframe](iframe-checkout.html)

Sample for customizing theme and colors of the form:

* [Customization](customization-checkout.html)

## Testing

You can use any of [the test card numbers](https://docs.pay.super.com/docs/payments/testing/#test-card-numbers) to test a `successful` or `failed` payment with `3-D Secure` and `Non 3-D Secure` test cards.

## Contributing, Feature Requests and Support

If you like this project then you can put a ⭐ on it. It means a lot to us.

If you have an idea of how to improve PaySuper (or any of the product parts) or have general feedback, you're welcome to submit a [feature request](../../issues/new?assignees=&labels=&template=feature_request.md&title=).

Chances are, you like what we have already but you may require a custom integration, a special license or something else big and specific to your needs. We're generally open to such conversations.

If you have a question and can't find the answer yourself, you can [raise an issue](../../issues/new?assignees=&labels=&template=support-request.md&title=I+have+a+question+about+%3Cthis+and+that%3E+%5BSupport%5D) and describe what exactly you're trying to do. We'll do our best to reply in a meaningful time.

We feel that a welcoming community is important and we ask that you follow PaySuper's [Open Source Code of Conduct](https://github.com/paysuper/code-of-conduct/blob/master/README.md) in all interactions with the community.

PaySuper welcomes contributions from anyone and everyone. Please refer to [our contribution guide to learn more](CONTRIBUTING.md).


## License

The project is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
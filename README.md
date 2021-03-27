# Stripe Payment Modal Plain HTML Demo

This sample project shows how to implement Stripe payments & subscriptions within a modal dialog using [Payment Modal](https://paymentmodal.com) and plain old HTML.

### Demo

See a hosted version of this plain HTML demo project [here](https://plain-html.paymentmodal.com).

The hosted demo is running in Stripe test mode. Use `4242424242424242` as a test card number with any CVC + future expiration date.

## Getting Started

This is a site written in simple HTML and CSS.

## Installation

To see the Stripe modals in action, you need to create a free [Payment Modal account](https://app.paymentmodal.com/docs/getting-started).

1. Clone this repo.
2. In the project directory, open `index.html` to view it in the browser. Copy the hostname (i.e. `http://localhost:3000`).
3. Create a new [Payment Modal site](https://app.paymentmodal.com/docs/getting-started), set the domain as hostname from step 2.
4. Add at least one modal to your Payment Modal site with an Amount, set the HTML Selector as `#pm-payment-amount`.
5. Refresh your page `index.html` in the browser and click on the "Amount Charge" button to open the modal.

This sample and hosted demo project uses the following HTML element attributes, but you can use any valid [HTML selector](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors#reference_table_of_selectors). Be sure to update the selectors in your Payment Modal account.

- `buttonId` creates a modal with a Stripe payment intent using an amount.
- `className` creates a modal with a Stripe payment intent using a Stripe price id.
- `dataSubscriptionCheckout` creates a modal with a Stripe subscription using a Stripe price id.

## Learn More

You can learn more about configuring Stripe modal properties in the [Payment Modal documentation](https://paymentmodal.com/docs).

#### Get Support

If you found a bug or want to suggest a new [feature/use case/sample], please [file an issue](https://github.com/funnelkake/stripe-payment-modal-plain-html-example).

If you have questions, comments, or need help with the code, we're here to help:

on Twitter at [@paymentmodal](https://twitter.com/paymentmodal)
on Stack Overflow at the stripe-modal tag
by [email](mailto:support@paymentmodal.com?subject=[GitHub]%20Source%PlainHTML%20Demo)

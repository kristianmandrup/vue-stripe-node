# vue-stripe-node
Quick demo for implementing stripe checkout in Vue.js and Node/Express

Super simple. Intentionally not using any task-runners or module-loading tools. Good ol' npm and external libraries loading via a CDN. Not fancy (obviously, not even production ready) but should be a VERY clear demo.

## To Install
1. clone
2. npm install
3. create file *.env* based on *.env.sample* with your own Stripe credentials
4. *node server.js* or *nodemon* or whatever-you-like-to-use
5. navigate your favorite browser to http://localhost:9002

## Testing

[Testing cards and payments](https://stripe.com/docs/testing)

- `4242424242424242` VISA
- `5555555555554444` Mastercard
- `4000002080000001` tok_dk	Denmark (DK) Visa
- `4000008260000000` tok_gb	United Kingdom (GB)	Visa

## Stripe Reference Docs

https://stripe.com/docs/checkout#integration-custom

Note: if you want to run Stripe in *live mode*, this example must be deployed to a server with SSL cert. My own preferences in this matter lie squarely with https://letsencrypt.org/

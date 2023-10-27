
[![Netlify Status](https://api.netlify.com/api/v1/badges/a73f5bfa-e0e4-471f-845e-1e7684194e74/deploy-status)](https://app.netlify.com/sites/stripe-netlify-accept-a-payment-react/deploys)

# Stripe Accept a payment boilerplate for Netlify 

Demo available [here](https://main--stripe-netlify-accept-a-payment-react.netlify.app/)

This is a simple boilerplate for the [Stripe Accept A Payment](https://github.com/stripe-samples/accept-a-payment) Sample. 

To use this sample on Netlify from GitHub: 
* Clone the project into your GitHub profile
* Go on your Netlify console and click "Add a new site"
* Click "Deploy with GitHub"
* Select the repo you cloned
* Set the following Build settings:
  * Base Directory: leave empty
  * Build Command: `react-scripts build`
  * Publish directory: `build` (don't blame me for the name. I'm keeping it consistent with the sample app)
  * Functions directory: leave prefilled value (`netlify/functions`)
* Click on `Environment Variable` button and add the following environmental variable
  * `STRIPE_PUBLISHABLE_KEY`: your Stripe publishable key
  * `STRIPE_SECRET_KEY`: your stripe secret key
* Click Deploy button




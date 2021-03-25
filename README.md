# Razorpay Payments 🚀💶

Easiest way to add Razorpay payments in your Next.js / React / Node.js applications.
Note: Webhooks not implemented yet, it requires

## Usage

- Head over to [Razorpay](https://razorpay.com) and create an account

- Generate the [API keys](https://https://dashboard.razorpay.com/app/keys) which can be found in the `Test Mode` dashboard

- Save the API keys in an environment file, example of it is provided in the source code here.

- Create an instance of razorpay at the front-end, we fetch the order_id, amount and currency from the serverless function (back-end).

Note: `Webhooks` not yet implemented, use ngrok to locally install a secure ssh tunnel, then use that URL to create a `Webhook` in the Razorpay Dashboard.

##

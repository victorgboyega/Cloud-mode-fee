# Cloud Mode Fee + Flutterwave

This version connects the payment form to Flutterwave Standard checkout.

1. Create/verify a Flutterwave merchant account.
2. Copy `.env.example` to `.env`.
3. Put your Flutterwave secret key in `FLW_SECRET_KEY`.
4. Set `PUBLIC_URL` to the real HTTPS domain of this website.
5. Run `npm install`, then `npm start`.
6. Configure your Flutterwave redirect/webhook settings as appropriate.
7. Before treating a payment as successful, verify the transaction server-side.

Never put the secret key in browser JavaScript or commit `.env` to source control.
Use Flutterwave test credentials first, then switch to live credentials after testing.

E-commerce website built with Next.js, Node.js, React.js and Bootstrap! MongoDB is used as the DBMS.

To run locally, provide a correct `MONGODB_URL` in `next.config.js`. You can copy the code below and put it in the `next.config.js` file:
```
module.exports = {
    env: {
        "BASE_URL": "http://localhost:3000",
        "MONGODB_URL": "YOUR_MONGODB_URL",
        "ACCESS_TOKEN_SECRET": "YOUR_ACCESS_TOKEN_SECRET",
        "REFRESH_TOKEN_SECRET": "YOUR_REFRESH_TOKEN_SECRET",
        "PAYPAL_CLIENT_ID": "YOUR_PAYPAL_CLIENT_ID",
        "CLOUD_UPDATE_PRESET": "YOUR_CLOUD_UPDATE_PRESET",
        "CLOUD_NAME": "YOUR_CLOUD_NAME",
        "CLOUD_API": "YOUR_CLOUD_API"
    }
}

```

Then:
```
npm install
npm run dev
```

You can view it on your favourite web browser in `http://localhost:3000`. Enjoy!

This app is also deployed on [Vercel](https://buyzilla-mmk-1.vercel.app)


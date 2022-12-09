# DRESS SHOP

## A full stack e-commerce website for agriculture store

## Stacks

- TypeScript
- Next js
- Node js
- Express js
- MongoDB
- Cloudinary (for image hosting)
- Stripe and Paypal (for payment)
- Vercel (for deployment)

### Client Installation

``` sh
cd 
cd client
npm install or yarn install
```

#### Add .env.local file to root client directory

```sh
NEXT_PUBLIC_PAYPAL_CLIENT_ID=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KY=
NEXT_PUBLIC_GOOGLE_CLIENT_ID=
```

## Server Installation

```sh
cd server
npm install or yarn install
```

### Add .env file to root server directory

```sh
DATABASE_URI=
JWT_SECRET=
STRIPE_SECRET_API_KEY=
GOOGLE_WEB_CLIENT_ID=
GOOGLE_ANDROID_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
CLIENT_PUBLIC_URL=
CLOUDINARY_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
PAYPAL_CLIENT_ID=
PAYPAL_CLIENT_SECRET=
```

### This will run both client and server

```sh
npm run dev
```

## Deploy using vercel

### Globally install vercel

```sh
npm i -g vercel
```

### Client

```sh
vercel --prod
```

## Server

```sh
vercel --prod
```

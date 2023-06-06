## Getting Started

### Features:

- Tailwind design, Tailwind animations and effects
- Credential / Google / Github authentication
- Image upload using `Cloudinary CDN`
- Client form validation and handling using `react-hook-form`
- Server error handling using `react-toast`
- Calendars with `react-date-range`
- Booking / Reservation system
- Guest reservation cancellation
- Owner reservation cancellation
- Creation and deletion of properties
- Advanced search algorithm by category, date range, map location, number of guests, rooms and bathrooms
    - For example we will filter out properties that have a reservation in your desired date range to travel
- Favorites system
- How to write POST and DELETE routes in route handlers (app/api)
- How to fetch data in server react components by directly accessing database (WITHOUT API! like Magic!)

### Tech Stack
- React
- NextJS
- Tailwind
- MongoDB
- Prisma
- Zustand
- TypeScript

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone git@github.com:omrsfylmz/full-stack-airbnb-clone.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_SECRET=
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |

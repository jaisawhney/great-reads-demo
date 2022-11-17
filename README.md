# Great Reads

Being an avid reader is not just a hobby or an interest - it is a lifestyle.

Great Reads is a one stop shop for everything reading related:

- Save and track books you’ve read
- Share your books with your friends
- Leave reviews
- Set daily reading goals
- Track progress

---

Enjoy the current iteration of Great Reads [Here!](https://great-reads-qacg-lartg.vercel.app/)

## Project timeline

- September - CRUD resources/environment setup

- October - release product with limited features and styling

- November - Add features, tailor styling

---

## Getting Started

**After cloning the repo:**

### Install dependencies:

```bash
npm install
```

Make sure you have MySQL installed and a server running on port 3306!

### Add Environment Variables:

##### in .env

- DATABASE_URL

##### in .env.local

- AUTH0_SECRET
- AUTH0_BASE_URL
- AUTH0_ISSUER_BASE_URL
- AUTH0_CLIENT_ID
- AUTH0_CLIENT_SECRET

### Migrate the database schema with:

```bash
npx prisma migrate dev
```

### Then, run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

## Tools Used

- Next.js - [Documentation](https://nextjs.org/docs)
- Tailwind CSS - [Documentation](https://tailwindcss.com/docs/installation)
- Auth0 - [Documentation](https://auth0.com/docs/)
- MySQL - [Documentation](https://dev.mysql.com/doc/)
- Prisma - [Documentation](https://www.prisma.io/docs/)

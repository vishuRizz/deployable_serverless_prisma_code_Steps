1. npm create cloudflare@latest
2.  npx wrangler whoami // confirmed that i am logged in else do npx wrangler login
3. npm install --save-dev prisma
4. npx prisma init
5.  npx prisma migrate dev --name init // this should say Your database is now in sync with your schema.
6.  npm install @prisma/extension-accelerate
// go to the prisma accelerate website put your neondb connection string the generate connection pooling string and paste it in .env file
7.  npx prisma generate --no-engine
// write your logic that you wanna deploy
8. npm run deploy
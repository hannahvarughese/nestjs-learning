# nestjs-learning
This is a project that was created to learn about NestJS. This project contains a user module with CRUD operations.

## Run the project
1. Clone the repository.
2. Do `npm install`
3. Go to [neon.tech](https://neon.tech), login/register and create a project. Choose prisma to be ORM. Copy the `.env` value from the dashboard and update it in code.
4. Initialize prisma using `npx prisma migrate dev --name update-schema`. This will create a migrations folder in prisma folder.
5. Run locally using `npm run start: dev`
6. Test the endpoints via postman (baseURL: http://localhost:3000/api)

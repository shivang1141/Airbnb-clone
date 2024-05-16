# Airbnb Clone

This is a clone of Airbnb, built with Next.js, Tailwind CSS, TypeScript, Prisma, and MongoDB.

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file:

- `DATABASE_URL`: URL for your MongoDB database
- `NEXTAUTH_SECRET`: Secret key for NextAuth.js
- `GITHUB_ID`: GitHub OAuth client ID
- `GITHUB_SECRET`: GitHub OAuth client secret
- `GOOGLE_CLIENT_ID`: Google OAuth client ID
- `GOOGLE_CLIENT_SECRET`: Google OAuth client secret
- `NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME`: Cloudinary cloud name

## Features

### User Management

- Create account with credentials
- Log in and log out functionality

### Accommodation Management

- Search and explore accommodations
- Apply combined filters (with buttons or in the search bar)
- Create and manage favorite accommodations

### Reservation Management

- Create and manage reservations for trips
- View and manage upcoming and past reservations

### Property Management

- Create a listing to rent your property
- Manage your properties (edit, update, delete)
- Manage reservations in your properties (accept, decline, message guests)


## License

[MIT](https://choosealicense.com/licenses/mit/)

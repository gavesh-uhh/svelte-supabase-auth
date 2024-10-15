# Svelte + Supabase Auth App

This is a simple authentication app using [Svelte](https://svelte.dev/) and [Supabase](https://supabase.com/) with Supabase JS for managing user sign-in, sign-up, and session handling.

## Features

- User sign-up, login
- Protected routes
- Supabase session handling

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- [Supabase account](https://supabase.com/) with a project created

### Installation

1. Clone the repository:

```bash
git clone https://github.com/gavesh-uhh/svelte-supabase-auth.git
cd svelte-supabase-auth
```

2. Install the dependencies:

```bash
npm install
```

3. Create a `.env.local` file in the root directory and add your Supabase credentials:

```bash
PUBLIC_SUPABASE_URL=https://your-supabase-url.supabase.co
PUBLIC_SUPABASE_ANON_KEY=your-anon-key
```

4. Run the app:

```bash
npm run dev
```

5. Open the app in your browser at `http://localhost:5173`.

## Usage

- **Sign Up**: Create an account using your email and password.
- **Login**: Log in with your email and password.
- **Protected Route**: Access protected pages after logging in.

## Supabase Setup

1. Go to your Supabase project dashboard.
2. Enable **Auth** and configure email/password sign-in.
3. Use the Supabase URL and anon key provided in the project settings.

## License

This project is open-source and available under the [MIT License](LICENSE).


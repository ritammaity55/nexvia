# Nexvia : A full-stack Job Portal Platform built using React JS, Tailwind CSS, Supabase, Clerk, Shadcn UI

## Introduction

Nexvia is a full-stack job portal platform that allows companies to post job listings and users to search and apply for jobs. The application provides features for both job seekers and employers, with user-friendly interfaces and secure authentication.
## Features

- **Job Listings:** Companies can post job listings, and users can browse and search for jobs.
- **Job Application:** Users can apply for jobs directly through the portal.
- **Authentication:** Secure login and registration using Clerk.
- **Responsive Design:** Built with Tailwind CSS for a seamless experience on any device.
- **Role-based Access:** Different views and actions for job seekers and recruiters.
- **Modern UI:** Designed using Shadcn UI components for a polished look.
- **Database Integration:** Supabase is used as the backend database for storing job listings, user data, and applications.

## Tech Stack

- **Frontend:**
  - React JS
  - Tailwind CSS
  - Shadcn UI
- **Backend:**
  - Supabase
- **Authentication:**
  - Clerk
- **Version Control:**
  - Git & GitHub
 
## Live Demo: [Click Here](https://nexvia.vercel.app/)


### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/ritammaity55/nexvia.git
2. **Change the directory to the following folder:**
    ```bash
    cd .\nexvia\
3. **Install dependencies:**
    ```bash
    npm install
    npm i @clerk/nextjs
    npm i @clerk/themes
    npm i dotenv
    npm i embla-carousel-autoplay
    npm i country-state-city
    npm i @uiw/react-md-editor
    npm i react-hook-form
    npm i zod
    npm i @hookform/resolvers
4. **Store the keys in the '.env' file**

    Create a .env file in the root directory of your project. Paste the Supabase URL in the VITE_SUPABASE_URL variable and the Supabase anonymous key in the VITE_SUPABASE_ANON_KEY variable. Next, login to your Clerk account to retrieve your Clerk Publishable Key, and paste it in the VITE_CLERK_PUBLISHABLE_KEY variable.
    ```bash
    VITE_SUPABASE_URL=
    VITE_SUPABASE_ANON_KEY=
    VITE_CLERK_PUBLISHABLE_KEY=
5. **Run the development server:**
   ```bash
    npm run dev

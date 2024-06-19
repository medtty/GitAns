# GitAns: Next.js 13, React, Socket.io, Prisma, Tailwind, MySQL | Full Course 2023

## Overview

In today's world, digital connection influences all areas of our lives, and education offers great opportunities for improvements. GitAns is an educational social networking platform that aims to redefine the way students learn, collaborate, and share knowledge. Through technology and community, GitAns allows learners to take charge of their own learning process and transcend conventional classroom boundaries.

## Features

- Real-time messaging using Socket.io
- Send attachments as messages using UploadThing
- Delete & edit messages in real time for all users
- Create text, audio, and video call channels
- 1:1 conversation between members
- 1:1 video calls between members
- Member management (kick, role change: Guest / Moderator)
- Unique invite link generation & full working invite system
- Infinite loading for messages in batches of 10 (tanstack/query)
- Server creation and customization
- Beautiful UI using TailwindCSS and ShadcnUI
- Full responsiveness and mobile UI
- Light / dark mode
- Websocket fallback: polling with alerts
- ORM using Prisma
- MySQL database using Planetscale
- Authentication with Clerk

## Prerequisites

- Node version 18.x.x

## Cloning the Repository

```sh
git clone git@github.com:medtty/GitAns-V2.3.6.git
```

## Install Packages

```sh
npm i
```
## Setup .env File
```sh
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
```

## Setup Prisma
Add MySQL Database (e.g., PlanetScale)

```sh
npx prisma generate
npx prisma db push
```

## Start the App

```sh
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |



GitAns is more than just a platform; it's a community-driven approach to modern education. By leveraging the power of technology and collective knowledge, GitAns is poised to transform learning experiences for students worldwide.
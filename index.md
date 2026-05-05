---
layout: default
title: UH GameLink
---
# UH GameLink

UH GameLink is a web application designed to help University of Hawaiʻi students connect with other students through video games. Many students play games casually or competitively, but it can be difficult to find other UH students with similar interests, schedules, or favorite games. This project aims to make it easier for students to meet new people, discover gaming communities, and build connections through shared games.

## Table of contents

* [Project Overview](#project-overview)
* [Project Goals](#project-goals)
* [Planned System Features](#planned-system-features)
* [Current Project Status](#current-project-status)
* [Initial Mockup Pages](#initial-mockup-pages)
* [Team Members](#team-members)
* [Team Contract](#team-contract)
* [Github Organization](#github-organization)
* [Deployment](#deployment)
* [M1](#M1)
* [M2](#M2)
* [M3](#M3)

## Project Overview

UH GameLink is a web application designed to help University of Hawaiʻi students connect with other students through video games. Many students play games casually or competitively, but it can be difficult to find other UH students with similar interests, schedules, or favorite games. This project aims to make it easier for students to meet new people, discover gaming communities, and build connections through shared games.

## Project Goals

The main goal of UH GameLink is to create a centralized place where students can:

- Build and customize a personal game library
- Share gaming preferences and interests
- Find other UH students who play the same games
- Discover gaming-related Discord servers, groups, and events
- Connect with others for casual play, teamwork, or community involvement

## System Features

As the project develops, the system is expected to provide:

- User accounts and profiles
- A personalized home page
- A video game library page
- A community page for gaming-related groups and resources
- A game request page for students searching for people to play with
- A player discovery page to find other users with similar games and preferences
- Administrative moderation and support features

These features are intended to help users not only organize their own gaming interests, but also actively connect with other members of the UH community.


## User Guide

Below are the screenshots of the working website and each of its functional pages. 

### Landing Page 
<p align="center">
<img src="img/M3/landing-pg.png" width="600px">
</p>
The landing page gives an overview of our app. As well as provides a directory to help users better navigate our website. Each card below the directory listing gives a description of the functionality for various pages and links to access those pages.

###  My Profile Page
<p align="center">
<img src="img/M3/profile-pg.png" width="800px">
</p>
 Shows User profile picture, profile description, and username, which can be edited. Additionally, the profile lists the User's games they have in their library.As well as displays their Interests & Communties(genres of video games, hobbies, etc.)

### Edit Profile Page
<p align="center">
<img src="img/M3/edit-profile.png" width="800px">
</p>
Whena user clicks on the "Edit Profile" link within the Profile page, it directs the users to create or edit their profile information in one page.Users can update their description and interests. Not only that, but they can upload and preview a profile picture before saving. Existing profile data is automatically loaded when editing. Finally, changes are saved to the database and reflected on the profile home page

### Game Library Page
<p align="center">
<img src="img/M3/game-library.png" width="800px">
(public library page)
<img src="img/M3/user-library.png" width="800px">
(user's library page)
</p>
This page lists a variety of different games. Each game shows an image of it, the name, a short description, and tags for it's game genre. When signed in, the user can add and view games in their favorites library. 

### Game Favorites Page
<p align="center">
<img src="img/M3/favorites-pg.png" width="800px">
</p>
To acess and edit a users favorites games, can click on the "view favorites" button in the game library or click the "Edit Favorites" link within the profile page. 

### Community Page
<div align="center">
<img src="img/M3/community-pg.png" width="800px">
<p>(public discord page)</p>
<img src="img/M3/user-community-pg.png" width="800px">
<p>(public user's page)</p>
</div>
the Community page displays a list of UH community discord servers, as well as various official disccords for specific games.
Each community card includes a server image, name, description, and tags. Users can join the discord by pressing the join discord button. When signed in, they can add these serves to their profile page listings under "Communities."

### Find Players Page
<p align="center">
<img src="img/M3/find-players.png" width="800px">
</p>
While signed in, this page hosts a list of UH GameLink users in the community. Each user card includes a profile image, username, game, and rank. Users can connect with each other through the "Connect" link. At the top right corner, users can search for specific players. in addition to viewing their requests to other players and create their own listing for the differant games they play. 

### Player Requests Page
<p align="center">
<img src="img/M3/requests-pg.png" width="800px">
</p>
While logged in, this page will allow the user to manages their requests to and from other users. The two functions of this page are to view other players requests to join gaming with the user and update their own request. 


### Reviews Page
<p align="center">
<img src="img/M3/review-pg.png" width="800px">
</p>
This page host a list of previous users of our site and their expirences with our plateform. With cars that display the user who wrote the review, their rating of our site, a description, date and date of the post. While logged in, this page will allow the user to leave and manages reviews of our site.

### Report Page
<p align="center">
<img src="img/M3/report-pg.png" width="800px">
</p>
The Report page allows users to file formal complaints about misconduct and harassment from other players on UH-GameLink. Users can detail information of the player's username, the grievance, and the date of the incident. The report will be sent to an admin moderator, where they will decide the standing of the player on UH-GameLink. 

### Report Dashboard Page
<p align="center">
<img src="img/M3/manage-pg.png" width="800px">
</p>

While logged in as an administrator, the moderator view the griences reported by users and handle issue on a case by case basis. After reviewing the detail of an incident, the moderator can resolve, flag the user for misconduct ("Conduct Warning" label will display on user cards), or Ban the player all together. 

### Manage Page
<p align="center">
<img src="img/M3/report-pg.png" width="800px">
</p>

While logged in as an administrator, the moderator can view all listing of UH-GameLink;s database information. They can alternate between managing and updating games to the Game library page. Or handle issues pretaining to the discord servers on the Community page. As well as moderate the standing and information listed within the FInd Players page. 

### Change Password Page
<p align="center">
<img src="img/M3/change-password.png" width="800px">
</p>

### Sign-in Page
<p align="center">
<img src="img/M3/sign-in.png" width="800px">
</p>

### Sign Out Confirmation Page
<p align="center">
<img src="img/M3/sign-out.png" width="800px">
</p>

### About Us Page
<p align="center">
<img src="img/M3/about-pg.png" width="800px">
</p>


## Community Feedback
<p align="center">
<img src="img/M3/review-pg.png" width="800px">
</p>
Description...

## Developer's Guide
<div style="max-width: 900px; margin: auto;">

<p>
  This section explains how to run UH GameLink locally and understand the project setup.
</p>

<h3>1. Prerequisites</h3>
<ul>
  <li>Node.js (v18 or higher recommended)</li>
  <li>npm</li>
  <li>PostgreSQL (local or hosted database such as Neon or Supabase)</li>
  <li>Git</li>
</ul>

<h3>2. Clone the Repository</h3>
<pre>
git clone &lt;https://github.com/uh-gamelink/uh-gamelink-app.git&gt;
cd &lt;uh-gamelink-app&gt;
</pre>

<h3>3. Install Dependencies</h3>
<pre>
npm install
</pre>

<h3>4. Environment Variables</h3>
<p>Create a <code>.env</code> file in the root directory:</p>

<pre>
DATABASE_URL="your-postgres-database-url"
NEXTAUTH_SECRET="your-secret-key"
NEXTAUTH_URL="http://localhost:3000"
</pre>

<h3>5. Set Up the Database</h3>
<pre>
npx prisma migrate dev
npx prisma generate
</pre>

<p>(Optional) Open Prisma Studio:</p>
<pre>
npx prisma studio
</pre>

<h3>6. Run the Development Server</h3>
<pre>
npm run dev
</pre>

<p>
  Open your browser and go to:
  <br />
  <a href="http://localhost:3000">http://localhost:3000</a>
</p>

<h3>7. Project Structure</h3>
<ul>
  <li><code>/app</code> → Pages (Next.js App Router)</li>
  <li><code>/components</code> → Reusable UI components</li>
  <li><code>/api</code> → API routes</li>
  <li><code>/lib</code> → Authentication + Prisma setup</li>
  <li><code>/prisma</code> → Database schema + migrations</li>
  <li><code>/public</code> → Static assets</li>
</ul>

<h3>8. Common Issues</h3>
<ul>
  <li>If Prisma errors occur, run <code>npx prisma generate</code></li>
  <li>If database connection fails, check <code>DATABASE_URL</code></li>
  <li>If login fails, ensure <code>NEXTAUTH_SECRET</code> is set correctly</li>
</ul>

</div>

## Team Members

- [Tuan Do](https://mtuando.github.io/)
- [John Gabriel Martinez](https://johngabrielmartinez.github.io/)
- [Ella Self](https://ellaself.github.io/)
- [Mason Vuong](https://mvuong808.github.io/)
- [Peyton Young](https://peytony9.github.io/)

## Team Contract

[View our Team Contract](https://docs.google.com/document/d/e/2PACX-1vRwtZI0GAWnwQ4oEau8QPwQtFm7aZ480nLDKV6xLEkga-hFvJbkGLqEwaJkZ7Y-P04amXjYO-S2kBL5/pub)

## Github Organization
[UH GameLink](https://github.com/uh-gamelink)

## Deployment
The UH GameLink application is deployed on Vercel and can be accessed here:

[https://uh-gamelink.vercel.app](https://uh-gamelink.vercel.app)

## M1 
 [M1](https://github.com/orgs/uh-gamelink/projects/2)

## M2
 [M2](https://github.com/orgs/uh-gamelink/projects/5)

## M3
 [M3](https://github.com/orgs/uh-gamelink/projects/7)

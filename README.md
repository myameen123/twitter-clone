# **Twitter Clone**

This project is a Twitter clone web application built with Next.js 13, Tailwind CSS, Pusher, Zustand, and Framer Motion. It aims to replicate the core features and functionality of Twitter, providing users with a similar experience of sharing tweets, following other users, and engaging in real-time conversations.

## **Features**

- **User Authentication:** Users can create accounts, log in, and securely authenticate their identities to access the full functionality of the Twitter clone.
- **Timeline:** The timeline displays a chronological feed of tweets from the user and the accounts they follow, allowing users to stay updated with the latest posts.
- **Tweeting:** Users can compose and publish tweets, including text, images, and hashtags, and share them with their followers.
- **Real-time Updates:** Leveraging Pusher, the application provides real-time updates to users' timelines and notifications, ensuring an interactive and dynamic user experience.
- **Follow and Unfollow:** Users can follow and unfollow other users to curate their timeline and connect with accounts of interest.
- **Likes and Retweets:** Similar to Twitter, users can like and retweet tweets to show their appreciation or share interesting content with their own followers.
- **Responsive Design:** The application is built using Tailwind CSS, ensuring a responsive and visually appealing layout across various devices and screen sizes.

## **Technologies Used**

- **Next.js 13:** Next.js is a React framework that provides server-side rendering, optimized routing, and other performance-enhancing features for building robust web applications.
- **Tailwind CSS:** Tailwind CSS is a utility-first CSS framework that enables rapid UI development with pre-defined classes and customizable styles.
- **Pusher:** Pusher is a platform for real-time communication that facilitates instant updates and notifications in the Twitter clone.
- **Zustand:** Zustand is a state management library that simplifies the management and sharing of application state across components.
- **Framer Motion:** Framer Motion is a library for creating smooth and interactive animations in the Twitter clone, enhancing the user interface and user experience.
- **MongoDB:** MongoDB is a non-SQL powerful database, used for the database with Prisma.

## **Getting Started**

1. Clone the repository: `git clone <repository-url>`
2. Install dependencies: `npm install`
3. Set up environment variables:
   ```env
   DATABASE_URL=<your-database-url>
   NEXTAUTH_SECRET=<your-nextauth-secret>
   PUSHER_APP_ID=<your-pusher-app-id>
   NEXT_PUBLIC_PUSHER_KEY=<your-next-public-pusher-key>
   PUSHER_SECRET=<your-pusher-secret>
   PUSHER_CLUSTER=<your-pusher-cluster>
   NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>
   NEXT_PUBLIC_HYGRAPH_ENDPOINT=<your-hygraph-endpoint>
   ```
4. Run the application: `npm run dev`
5. Open your browser and visit [http://localhost:3000](http://localhost:3000) to access the Twitter clone.

## **Contributing**

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request. Ensure adherence to the code style guidelines and provide clear and detailed information about the proposed changes.

## **License**

This project is licensed under the MIT License.

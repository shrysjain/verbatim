# Verbatim 📝

Verbatim is a secure and open-source realtime collaborative document editing application fully on the web, built with Next.js to handle the user interface, Liveblocks for real-time features, and styled with TailwindCSS.

## Features

- **Authentication**: User authentication using GitHub through NextAuth, ensuring secure sign-in/out and session management.
- **Collaborative Text Editor**: Multiple users can edit the same document simultaneously with real-time updates.
- **Documents Management**:
  - **Create Documents**: Users can create new documents, which are automatically saved and listed.
  - **Delete Documents**: Users can delete documents they own.
  - **Share Documents**: Users can share documents via email or link with view/edit permissions.
  - **List Documents**: Display all documents owned or shared with the user, with search and sorting functionalities.
- **Comments**: Users can add inline and general comments, with threading for discussions.
- **Active Collaborators on Text Editor**: Show active collaborators with real-time presence indicators.
- **Notifications**: Notify users of document shares, new comments, and collaborator activities.
- **Responsive**: The application is responsive across all devices.

## Try it out!

You can access Tether at [verbatimdocs.vercel.app](https://verbatimdocs.vercel.app). Enjoy!

If you'd like, you can run a development instance by cloning this repository, installing the dependencies with `npm`, and setting up `.env.local` with the following keys:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
LIVEBLOCKS_SECRET_KEY=
```

## Usage

- Authentication: Register or log in using Apple, Google, or email.
- Collaborative Editing: Open or create a document to start collaborative editing.
- Document Management: Create, delete, share, and list documents.
- Comments: Add comments and participate in discussions.
- Real-time Presence: See active collaborators in real-time.
- Notifications: Stay informed about document activities.

## Contributing

We welcome contributions to improve Verbatim. To contribute, please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

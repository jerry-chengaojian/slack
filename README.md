# Slack Clone

## 📝 Project Overview

This is a full-featured Slack clone built with modern web technologies, providing a real-time communication platform with robust features and a sleek user interface.

## 🚀 Features

- 🔐 Authentication & User Management
- 💬 Real-time Messaging
- 🔗 Channel Creation and Management
- 👥 Workspace Collaboration
- 📤 File Uploads
- 😀 Emoji Reactions
- 🌓 Dark/Light Mode Support

## 🛠 Tech Stack

### Frontend
- [Next.js 14](https://nextjs.org/) - React Framework
- [React](https://reactjs.org/) - UI Library
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [Radix UI](https://www.radix-ui.com/) - Unstyled, accessible components
- [Zustand](https://github.com/pmndrs/zustand) - State Management

### Backend & Database
- [Convex](https://www.convex.dev/) - Realtime Backend
- [Next Auth](https://next-auth.js.org/) - Authentication

### Additional Libraries
- [React Query](https://tanstack.com/query/latest) - Data Fetching
- [Quill](https://quilljs.com/) - Rich Text Editing
- [Sonner](https://sonner.emilkowal.ski/) - Toast Notifications

## 🏁 Getting Started

### Prerequisites
- Node.js (v18+)
- Bun or npm
- Convex Account

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/slack-clone.git
cd slack-clone
```

2. Install dependencies
```bash
bun install
# or
npm install
```

3. Set up environment variables
- Create a `.env.local` file
- Add necessary Convex and authentication configurations

4. Run the development server
```bash
bun dev
# or
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

# AI Chat Tool Frontend

A modern React + TypeScript frontend for an AI chat application with full Markdown support.

## Features

- 🚀 Built with React 18 and TypeScript
- 💬 Real-time chat interface
- 📝 Full Markdown support with syntax highlighting
- 🎨 Clean and responsive UI
- 🔗 GraphQL integration with Apollo Client
- 🎯 Type-safe development

## Prerequisites

- Node.js 16+
- npm or yarn
- Backend service running (see backend-ai-01 repository)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ljj0607/frontend-ai-01.git
cd frontend-ai-01
```

2. Install dependencies:
```bash
npm install
```

3. Copy environment variables:
```bash
cp .env.example .env.local
```

4. Update `.env.local` with your backend endpoint:
```
REACT_APP_GRAPHQL_ENDPOINT=your-backend-url/graphql
```

## Development

Start the development server:
```bash
npm start
```

The app will be available at [http://localhost:3000](http://localhost:3000)

## Building for Production

```bash
npm run build
```

The build artifacts will be stored in the `build/` directory.

## Testing

```bash
npm test
```

## Project Structure

```
src/
├── components/
│   ├── ChatContainer.tsx    # Main chat container
│   ├── MessageList.tsx      # Message list display
│   ├── MessageItem.tsx      # Individual message with Markdown
│   └── MessageInput.tsx     # Message input field
├── types/
│   └── index.ts            # TypeScript type definitions
├── App.tsx                 # Main App component
└── index.tsx              # Application entry point
```

## Technologies Used

- React 18
- TypeScript
- Apollo Client (GraphQL)
- React Markdown
- React Syntax Highlighter
- CSS3

## License

MIT

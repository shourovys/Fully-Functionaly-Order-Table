# Fully Functionaly Order Table

A modern, fully functional order table application built with Next.js 14 featuring advanced data tables with sorting, filtering, and responsive design.

## Live Demo

**Live Website:** [https://fully-functional-order-table-by-shourov-saha.vercel.app/](https://fully-functional-order-table-by-shourov-saha.vercel.app/)

**GitHub Repository:** [https://github.com/shourovys/Fully-Functionaly-Order-Table](https://github.com/shourovys/Fully-Functionaly-Order-Table)

---

## Key Features

- **Advanced Data Tables** - Feature-rich table component with sorting and filtering
- **Responsive Design** - Fully responsive layout using Tailwind CSS
- **Real-time Data** - SWR for efficient data fetching
- **Date Handling** - Date selection with react-tailwindcss-datepicker
- **Dropdown Menus** - Radix UI dropdown components
- **Tooltips** - Informative tooltips for better UX
- **Server-Side Rendering** - SSR with Next.js 14 for optimal performance
- **Type Safety** - Full TypeScript implementation
- **API Integration** - Axios for HTTP requests

---

## Technologies Used

- **Next.js 14** - App Router for modern React server components
- **React 18** - UI library with hooks
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first CSS framework
- **SWR** - Data fetching and caching
- **Axios** - HTTP client
- **Radix UI** - Unstyled UI components
  - @radix-ui/react-accordion
  - @radix-ui/react-dropdown-menu
  - @radix-ui/react-tooltip
- **Lucide React** - Icon library
- **date-fns / dayjs** - Date handling
- **qs** - Query string parsing
- **React Tailwind CSS Datepicker** - Date picker component

---

## Prerequisites

- Node.js 18.x or higher
- npm or yarn package manager

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone <repository-url>
cd Fully-Functionaly-Order-Table
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```

### 3. Environment Variables

Create a `.env.local` file if needed:

```env
NEXT_PUBLIC_API_URL=http://localhost:3000/api
```

### 4. Start Development Server

```bash
npm run dev
```

The app will be available at [http://localhost:3000](http://localhost:3000)

---

## Building for Production

```bash
# Build the application
npm run build

# Start production server
npm start
```

---

## Project Structure

```
Fully-Functionaly-Order-Table/
├── public/                   # Static assets
├── src/
│   ├── app/                 # Next.js App Router pages
│   │   └── page.tsx        # Main table page
│   ├── components/          # React components
│   │   ├── ui/             # Reusable UI components
│   │   └── table/          # Table-specific components
│   ├── hooks/              # Custom React hooks
│   ├── lib/                # Utility functions
│   ├── types/              # TypeScript types
│   └── utils/              # Helper functions
├── package.json
├── next.config.mjs
├── tailwind.config.ts
├── postcss.config.mjs
└── tsconfig.json
```

---

## Available Scripts

| Command         | Description              |
| --------------- | ------------------------ |
| `npm run dev`   | Start development server |
| `npm run build` | Build for production     |
| `npm run start` | Start production server  |
| `npm run lint`  | Run ESLint               |

---

## License

MIT License

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

# Better Nuxt GraphQL Starter Kit

A modern, production-ready starter template built with **Nuxt 4**, featuring GraphQL API, authentication, database management, file uploads, and state management.

## 🚀 Features

- **[Nuxt 4](https://nuxt.com)** - The latest version of the Vue.js meta-framework
- **[Nitro GraphQL](https://github.com/unjs/nitro-graphql)** - Native GraphQL support for Nitro server
- **[Better Auth](https://better-auth.com)** - Modern authentication system with social providers
- **[Drizzle ORM](https://orm.drizzle.team)** - TypeScript ORM with SQL-like syntax
- **[Pinia Colada](https://pinia-colada.vuejs.org)** - Smart data fetching and caching for Pinia
- **File Upload** - Built-in image/file upload handling with optimization
- **TypeScript** - Full type safety across the stack
- **Auto-imports** - Components, composables, and utilities auto-imported
- **SSR/SSG Ready** - Server-side rendering and static generation support

## 📋 Prerequisites

- Node.js 22+ 
- pnpm +10.13 (recommended) or npm/yarn
- PostgreSQL database (for Drizzle ORM)

## 🛠️ Installation

1. **Clone the repository**
```bash
git clone https://github.com/productdevbook/better-nuxt-graphql-starter-kit.git
cd better-nuxt-graphql-starter-kit
```

2. **Install dependencies**
```bash
pnpm install
```

3. **Environment Setup**

Create a `.env` file in the root directory:

```env
# Database
DATABASE_URL="postgresql://user:password@localhost:5432/dbname"

# Better Auth
AUTH_SECRET="your-auth-secret-here"
AUTH_URL="http://localhost:3000"

# OAuth Providers (optional)
GITHUB_CLIENT_ID=""
GITHUB_CLIENT_SECRET=""

# File Upload
UPLOAD_DIR="./uploads"
MAX_FILE_SIZE="10485760"  # 10MB in bytes
```

4. **Database Setup**

Initialize the database with Drizzle:

```bash
pnpm db:generate   # Generate migrations
pnpm db:migrate    # Run migrations
pnpm db:studio     # Open Drizzle Studio (optional)
```

## 🚀 Development

Start the development server:

```bash
pnpm dev
```

The application will be available at `http://localhost:3000`

### Available Scripts

```bash
pnpm dev          # Start development server
pnpm build        # Build for production
pnpm preview      # Preview production build
pnpm generate     # Generate static site
pnpm typecheck    # Run TypeScript type checking
pnpm lint         # Run ESLint
pnpm lint:fix     # Fix ESLint issues
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Nuxt Team](https://nuxt.com) for the amazing framework
- [UnJS](https://unjs.io) for Nitro and ecosystem tools
- [Better Auth](https://better-auth.com) for authentication
- [Drizzle Team](https://orm.drizzle.team) for the ORM
- [Vue Team](https://vuejs.org) for Vue.js and Pinia

## 📞 Support

- 📧 Email: support@example.com
- 💬 Discord: [Join our server](https://discord.gg/example)
- 🐛 Issues: [GitHub Issues](https://github.com/productdevbook/better-nuxt-graphql-starter-kit/issues)

---

Built with ❤️ by [productdevbook](https://github.com/productdevbook)
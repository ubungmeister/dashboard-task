# React/Next.js Developer Technical Task

## Project: Task Management Dashboard

### Overview
Your task is to create a **Task Management Dashboard** using **Next.js** and **React**. The dashboard should allow users to **view, add, edit, and delete tasks** with minimal UI but well-structured code.

---
## Requirements

### 1. Task List Page
- Fetch tasks from `public/tasks.json`.
- Display tasks in a **table** or a **card-based layout**.
- Show task details:
  - **Title**
  - **Description**
  - **Priority** (Low, Medium, High)
  - **Status** (To Do, In Progress, Done)

### 2. Task Management
- User should be able to:
  - **Add** a new task
  - **Edit** an existing task
  - **Delete** a task

### 3. Filtering & Sorting
- Implement **filtering by status** (To Do, In Progress, Done).
- Implement **sorting by priority** (Low → High, High → Low).

### 4. Persistent State
- Use **React Context** or **@tanstack/react-query** to manage state.
- The task list should persist **even after a page refresh**.

### 5. Bonus (Optional, if you have time)
- Implement **Drag and Drop** for changing task status.
- Add **local storage** to persist tasks.

---
## Notes
- This project is **meant for a single user** (no authentication required).
- Local storage is sufficient for persistence in this test task.
- Keep the UI simple but clean and responsive.
- Focus on **code structure and best practices**.

Good luck! 🚀


## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

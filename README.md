# MarkdownBlog

A modern blog platform with markdown support and community engagement

## Project Vision

A simple blog platform with:
- User authentication
- Create and edit posts
- Markdown support
- Comments

## Tech Stack

**Frontend**: Next.js 14 + TypeScript + Tailwind CSS + react-markdown + react-simplemde-editor
**Backend**: Node.js + Express + PostgreSQL + Prisma ORM + bcrypt + jsonwebtoken
**Deployment**: railway

## Features

1. **User Authentication System** - Registration, login, JWT-based authentication, and session management with secure password hashing
2. **Post Creation and Editing** - Rich markdown editor with live preview, auto-save drafts, publish/unpublish functionality, and slug generation
3. **Markdown Rendering** - Safe markdown-to-HTML conversion with syntax highlighting, sanitization, and support for images, links, and code blocks
4. **Blog Post Listing** - Paginated list of published posts with search, filtering by author, and sorting by date
5. **Comment System** - Nested comment threads with edit/delete for authors, real-time updates, and markdown support in comments
6. **User Dashboard** - Personal dashboard showing user's posts with draft/published status, edit access, and analytics
7. **Post Permalink Pages** - SEO-optimized individual post pages with metadata, social sharing tags, and comment sections
8. **Authorization Guards** - Middleware ensuring users can only edit/delete their own posts and comments
9. **Input Validation** - Server-side validation for all user inputs including post content, comments, and authentication data
10. **Responsive Design** - Mobile-first responsive layout optimized for reading and writing on all device sizes

## Status

This project is being built automatically by [ShipStack](https://shipstack.ai) AI agents.

- Jules: Building features
- Claude Code / Cursor: Testing and refining

---

Built with ShipStack 🚀

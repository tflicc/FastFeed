# FastFeed

A Reddit clone with hashtags instead of subreddits.

# 🗺️ Roadmap
---

## ✅ Phase 1 – MVP (Frontend-Only)

**Goal:** Build a static, in-browser version with no backend.

- [ ] Basic app layout (header, post list, post form)
- [ ] Angular routing (`/`, `/submit`, `/post/:id`)
- [ ] Display feed of hardcoded posts
- [ ] Upvote/downvote buttons (frontend only)
- [ ] Tag display on posts
- [ ] Filter posts by tag (dropdown or buttons)
- [ ] Post submission form (adds post to in-memory list)

---

## 💾 Phase 2 – Local Storage Persistence

**Goal:** Save post data, votes, and tags using `localStorage`.

- [ ] Save posts and votes to `localStorage`
- [ ] Load post data from `localStorage` on app load
- [ ] Persist new post submissions
- [ ] Persist voting interactions

---

## 🔌 Phase 3 – Backend Integration

**Goal:** Store and fetch real data from a backend (Firebase or custom API).

- [ ] Choose backend platform (Firebase or Node.js + MongoDB)
- [ ] Set up project and connect Angular via `HttpClient`
- [ ] Submit new post to backend
- [ ] Fetch post feed from backend
- [ ] Store votes (optional: per user/IP)
- [ ] Upload and serve media files (images at minimum)

---

## 💬 Phase 4 – Comment System

**Goal:** Add threaded user comments to posts.

- [ ] Add comment section to post view
- [ ] Build nested comment UI (1–2 levels)
- [ ] Submit comments (frontend-only at first)
- [ ] Optional: Persist comments to backend
- [ ] Add voting to comments

---

## 🔐 Phase 5 – User Accounts & Authentication

**Goal:** Allow users to register, log in, and track their content.

- [ ] User registration form
- [ ] User login/logout
- [ ] Show current user status in header
- [ ] Restrict voting/posting to logged-in users
- [ ] Display author on posts and comments

---

## 🌟 Optional Stretch Goals

Polish and advanced features (only after the core app is working):

- [ ] Media previews for video/audio
- [ ] Markdown support in posts/comments
- [ ] User profile pages (show posts/comments)
- [ ] Admin/moderator tools
- [ ] Report/flag content
- [ ] Infinite scroll or pagination
- [ ] Dark mode toggle

# 🧠 Copilot Instructions — ProcureFlow

## 🏗️ Tech Stack

* Next.js (App Router)
* TypeScript (strict)
* Tailwind CSS + shadcn/ui
* Supabase (Auth + DB)
* Vercel

---

## 📁 Project Structure

* `app/` → routing
* `features/` → business modules (MAIN SOURCE)
* `components/` → UI only
* `hooks/` → reusable logic
* `services/` → business + DB logic
* `policies/` → RBAC enforcement
* `lib/` → utilities (supabase, auth, helpers)
* `config/` → roles & permissions
* `types/` → global types
* `middleware.ts` → auth + workspace guard

Feature structure:

```
feature/
  ├── components/
  ├── hooks/
  ├── services/
  └── types.ts
```

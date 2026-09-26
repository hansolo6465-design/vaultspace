# Vaultspace — Supabase

Real frontend backed by Supabase Auth, Postgres, Storage and RLS.

## Setup
1. Open `supabase/schema.sql`.
2. In Supabase → SQL Editor, run the complete SQL file.
3. In `script.js`, replace `YOUR_SUPABASE_URL` and `YOUR_SUPABASE_PUBLISHABLE_OR_ANON_KEY`.
4. Enable Email authentication in Supabase → Authentication → Providers → Email.
5. Upload the project to GitHub/Vercel.
6. Never put a `service_role` or secret key in `script.js`.

The current build includes real login/signup, persistent notes, private file uploads/downloads, and room creation/membership. More collaboration features can be added on this database foundation.

RASEL PORTFOLIO V3

NEW:
1) Visitor count
2) "Drop a Note" floating button
3) Message modal stays inside the website — no mail app / no external page.
4) Real shared visitor count and real message storage are supported with Supabase.

QUICK SETUP FOR REAL DATA:
A) Create a free Supabase project.
B) Open SQL Editor and run supabase_setup.sql.
C) In index.html replace:
   YOUR_SUPABASE_URL
   YOUR_SUPABASE_ANON_KEY
   with your project's URL and anon/public key.
D) Replace YOUR_EMAIL and the 7 social "#" links with your own details.
E) Upload the folder to Vercel/Netlify/GitHub Pages.

IMPORTANT:
- Until Supabase is configured, the visitor count is only a local browser demo.
- The message form also works as a visual demo until Supabase is configured.
- Never put a Supabase service_role/secret key in frontend code. Use only the anon/public key.
- You can read incoming messages from Supabase Table Editor.

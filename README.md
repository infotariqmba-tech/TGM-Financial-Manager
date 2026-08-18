# TGM Financial Manager

Cloud accounting MVP using Supabase Auth + PostgreSQL.

1. Run `setup_part3.sql` in Supabase SQL Editor.
2. Copy `config.example.js` to `config.js`.
3. Put your Supabase **Publishable key** in `config.js`.
4. Host this folder on a static host so the same login works on phone and computer.
5. Create an account, then use Company Setup.

Never put a Supabase service_role/secret key in browser code.

Included: login/signup, company setup, chart of accounts, contacts, projects, double-entry journal, dashboard and trial balance.

For long-term protection, enable Supabase database backups/PITR.

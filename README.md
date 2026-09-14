# The Angler's Register — site

The built page only. A family fishing journal for Brandon Jones and his sons,
kept in Idaho.

Everything the page shows — entries, plates, species, map pins — is read at
runtime from a Supabase project. The key embedded here is the **anon** key,
which is public by design: the register is deliberately readable by anyone with
the link, and every write is gated by row level security plus family membership.

Source, migrations and ingest scripts live outside this repository.

## Get Started Locally
https://supabase.com/docs/guides/cli/local-development
1. Make sure supabase is installed with 'npm install supabase --save-dev'
2. Login if needed with 'npx supabase login'
3. Switch to point to the correct supabase project
4. Run 'npx supabase start' to start the local server
5. Run 'npx supabase stop' to stop the local server


## Default migrations
Several migrations are run by default to build a basic app. This includes functions to create a profile table, insert on new user creation, RLS on user avatars.

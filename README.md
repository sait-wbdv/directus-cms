# directus-cms
An open source frontend for course content.

## Setup Instructions
1. Create an env file with the following content (gathered from supabase/settings/database) 
  - Database Host – The IP address for your database.
  - Port – Port number your database is running on. `5432`
  - Database Name – Name of your existing database. `postgres`
  - Database User – Name of existing user in database. `postgres`
  - Database Password – Password to enter database.
  - Enable SSL – Select  N for no
  - Root – The root name.
2. run directus with `npx directus start`


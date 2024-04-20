 <h2 align="center">Firebase Realtime db Data Migration to supabase </h2>

<p align="center"> Effortlessly Migrate your firebase realtime database data to supabase </p>

## Demo Video

![Alt text](Demo/demo.mp4)

## Getting Started

### Export Data from Firebase:
1. Go to your Firebase dashboard and navigate to the Realtime Database section.
2. **Choose the specific database path you want to export**
3. On the right side, click on "Export".
4. Visit [Firebase realtimedb to supabase web](https://firebase-realtimedb-to-supabase.vercel.app/) and upload your exported JSON format from Firebase.
5. Click "Generate Column Titles" and carefully read the instructions on the page.

### Prepare Supabase:
1. Go to your Supabase dashboard.
2. Create a table of your choice in your Supabase database.
3. Make sure to turn off row-level security for this table.
4. Add the column titles and their data types as they were generated on the website page.

### Push Data to Supabase:
1. Return to the {website} and click on the "Push Data" button.
2. Enter the name of the table you created on your Supabase database dashboard.
3. Provide the project URL obtained from Supabase.
4. Include the API key as well.
5. Click the button below to start uploading your JSON data. You'll see a progress bar indicating the transfer status.


## Authors

- [@itsallan](https://github.com/itsallan)
- [@lauben2814y](https://github.com/lauben2814y)
## Badges
[![Made with Supabase](https://supabase.com/badge-made-with-supabase-dark.svg)](https://supabase.com)

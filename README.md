# SUMOM Bright Coaching Center — Front-end Demo v2

## Included
- Public website: Home, About, Courses, Classes & Batches, Routine, Exams & Results, Notices, Gallery, Resources, Contact
- Separate class/course and batch detail pages
- Admin Panel + Admin Control Panel
- Neon/RGB/glass/floating visual system with reduced-motion support
- Teacher portrait added from the uploaded image
- Front-end demo state using localStorage
- Demo CRUD for courses, notices, routine and gallery metadata
- Demo backup/export
- Search/filter controls
- Phone tap-to-call, Facebook link and Google Maps link

## Important before publication
1. Provide the custom admin demo email and password. They are intentionally blank in `assets/js/demo-auth.js`.
2. Confirm the final phone number before publishing. Current demo: 01720811644.
3. Replace `example.com` in `sitemap.xml` with the real GitHub Pages/custom domain.
4. Connect Supabase Auth + database + RLS for real admin authentication and CRUD.
5. Connect the Google Drive OAuth/storage routing layer through secure server-side/Edge Function logic. Never put service-role keys, OAuth secrets or Google passwords in frontend code.
6. Replace demo course fees and routine with final data.

## Branding
- Logo text: `SBCC`
- English brand spelling requested: `SUMOM Bright Coaching Center`
- Full English teacher name: `Md Sumon Hossain`
- Bangla teacher name: `মোঃ সুমন হোসেন`
- Tagline: `শিক্ষা • অনুশীলন • সফলতা`

## Front-end demo note
Admin changes are browser-local and are intended for presentation/testing only. They do not yet modify a shared online database.

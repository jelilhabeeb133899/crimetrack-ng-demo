CRIMETRACK NG — STUDENT DEMONSTRATION PROTOTYPE

Files:
- index.html: single-file responsive prototype for Android and desktop browsers.

CURRENT FEATURES:
- Home/overview
- Guest-style demonstration crime report form
- Generates a demo reference number
- Tracking form
- Prototype officer dashboard
- Status updates stored in the browser's localStorage

IMPORTANT LIMITATIONS:
- This is a FRONT-END PROTOTYPE only. Reports are stored only in the same browser on the same device.
- The demo dashboard PIN is visible in the source and is NOT security.
- It has no server, real database, account registration, real login, secure evidence storage, email/SMS notifications, or official police connection.
- Do not enter real names, phone numbers, addresses, evidence, or confidential police information.
- Do not use as an emergency service or for real case handling.

HOW TO OPEN ON ANDROID:
1. Download and extract the ZIP file using your phone's Files app.
2. Open index.html with a browser or a code editor with HTML preview. Some Android file managers may not allow scripts to run from local files; if so, use an HTML editor app with preview or wait until you have internet and deploy it.
3. Reports are local to that browser/device and may be lost if browser data is cleared.

HOW TO DEPLOY LATER:
For a real multi-user app, the next version must use a server-side backend and database, e.g. PHP + MySQL. Uploading this HTML file alone creates only a demonstration site; it does not provide secure user accounts or shared reports.
A static host such as GitHub Pages can publish the current HTML demo but cannot run PHP/MySQL. For PHP/MySQL, choose a host that explicitly supports both, configure the database, then upload files to the host's web root. Check current host policies before relying on a free plan.

Before any public launch:
- Add server-side validation and secure authentication.
- Store passwords using password_hash/password_verify.
- Use prepared SQL statements.
- Add role-based access control, CSRF protection, rate limiting, audit logs, backups, HTTPS, and secure evidence uploads.
- Define privacy, retention, moderation, and escalation procedures.
- Obtain proper authorisation before using police branding or handling actual reports.

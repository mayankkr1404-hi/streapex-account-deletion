STREAPEX ACCOUNT DELETION WEBSITE — GITHUB PAGES

FRONT-END ONLY
This version is prepared for GitHub Pages. Submitting the form opens the visitor's email application with a deletion request addressed to streapex14@gmail.com. The visitor must send the email; a request is not received until then. If their device has no email app configured, they can email that address manually.

This site does not automatically delete Firebase Authentication users, Firestore data, or Supabase data. The backend and deletion workflow can be added in a later update.

PUBLISH USING GITHUB PAGES
1. Sign in at https://github.com/.
2. Create a new Public repository named streapex-account-deletion.
3. Open the repository and choose Add file > Upload files.
4. Upload index.html and README.txt from this folder. Ensure index.html is at the repository root, not inside a nested folder.
5. Click Commit changes.
6. Open Settings > Pages.
7. Under Build and deployment, set Source to Deploy from a branch.
8. Select branch main and folder /(root), then click Save.
9. Wait for deployment. Under Settings > Pages, click Visit site.
10. Your URL will look like https://YOUR-GITHUB-USERNAME.github.io/streapex-account-deletion/
11. Test the public URL on phone and desktop. Test the form and send a test email to confirm it reaches streapex14@gmail.com.

IMPORTANT FOR GOOGLE PLAY
Use the public HTTPS URL only after verifying it loads publicly and the email-request route works. This is a front-end-only interim approach. Requests must actually be processed and the account and associated data deleted; the page itself does not perform deletion.

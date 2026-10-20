# CareDesk public demo

This is a static, public-safe demonstration page for GitHub Pages. It is separate from the working CareDesk server.

- Uses only sample, browser-local replies; no AI service is connected.
- Does not connect to patient records, booking storage, Excel, Gmail, SMTP, or OAuth.
- Do not enter real patient or health information.
- The public link will be accessible to anyone and is not a production clinic service.

## Publish with GitHub Desktop

1. Open GitHub Desktop and choose **File → Add local repository**. Select this folder. If prompted, choose the option to create a repository in this folder.
2. Commit the files to the default branch.
3. Choose **Publish repository**. A free GitHub Pages site requires a public repository on GitHub Free. Publish this demo repository publicly; do not add any other CareDesk project files.
4. On the repository's GitHub page, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose the default branch and **/(root)**, then save.
5. Wait for the Pages deployment to finish. GitHub displays the published address under **Settings → Pages**. A project site address follows `https://<account-name>.github.io/<repository-name>/`.

GitHub Pages serves static files only. It cannot run the CareDesk server, persist bookings, or send Gmail messages.

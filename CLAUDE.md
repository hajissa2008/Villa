# Villa repo: working rules
- This PUBLIC repo holds only the locked villa viewer: `index.html` (sign-in page) and `villa.bin` (the encrypted model). Never commit the plain viewer, the DWG, PDFs, renders, or the username and password.
- The plain viewer is generated from the 4D Modeling Platform on the owner's PC (`Downloads\4D Modeling Project\platform`).
- Sync rule (requested by the owner): after ANY change to the villa model, rebuild the plain viewer, lock it with `tools/lock.js` (ask the owner for the page's username and password; they are not stored anywhere), and publish it here.
- Keep the history to a single commit (amend and force-push), so no earlier file stays in the repository.

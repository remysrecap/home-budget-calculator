# Home budget calculator

A responsive mortgage and down-payment calculator. Start at zero, save scenarios automatically on this browser, and use Settings → Invite to load an encrypted starting snapshot.

The invite is a starting copy, not live syncing. Changes on one phone do not update another. Clearing browser storage removes local scenarios. Settings → Invite → Export saved scenarios downloads a private backup containing financial details.

The public site contains no plaintext starting financial values or invite code. The shared snapshot is decrypted locally with AES-256-GCM and a PBKDF2-SHA256 key (600,000 iterations). An easily guessed code still offers limited protection against offline guessing.

To publish with GitHub Pages, serve these files from the main branch root. No build step or paid service is required.

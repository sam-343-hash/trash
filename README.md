Certificate Vault

A simple page for storing your certificates (PDFs) and sharing them with a link — no login required for people you share with.

Files
certificate-vault.html — the vault itself. Open this in Claude to publish it as a live page, or open the HTML file directly in a browser to use it locally.
How to use it
Open the artifact. In Claude, open certificate-vault.html and publish it (or ask Claude to publish it for you). This gives you a private link only you can see at first.
Add a certificate. Click "Add certificate," fill in the name (required) and optionally the issuer and date, then choose a PDF file.
Max file size: ~3.5 MB per certificate.
View a certificate. Click any certificate in the left-hand list to preview it.
Share a certificate. With a certificate open, click "Copy share link." This copies a link that opens directly to that certificate. Send this link to anyone — they don't need a Claude account to view it.
Delete a certificate. Open it, then click "Delete." This can't be undone.
Important: sharing and privacy
The vault uses shared storage, meaning anyone who has the artifact's link can see every certificate stored in it, not just the one they were sent.
There's no password or access control — treat the link like a public document link. Only share it with people you're comfortable seeing your certificates.
If you want tighter access control (e.g. expiring links, per-person permissions), that would need a different setup — let Claude know if you'd like to explore that.
Known limits
File size: PDFs over ~3.5 MB are rejected. If you have a larger certificate, consider compressing it first, or ask Claude for help splitting/compressing it.
File type: Only PDF is currently supported.
No offline access for viewers: the link only works while the artifact is published and reachable.
Troubleshooting
"Could not save the certificate" — usually means the file was too large, or a temporary storage issue. Try again, or shrink the PDF.
A shared link shows nothing — the certificate may have been deleted since the link was shared.

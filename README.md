# ID Vault

A personal vault for keeping site accounts, social IDs and card details in one place.

- All data is stored only in the browser's local storage on your own device, encrypted with AES-GCM (key derived from a master password with PBKDF2, 600,000 iterations).
- The master password itself is never stored anywhere. Nothing is sent to any server.
- Paste a URL and the service is detected from its domain. For X, TikTok and YouTube, the permanent ID (the one that survives a username change) can be stored alongside the current username.
- Backup is a file export of the encrypted data only.

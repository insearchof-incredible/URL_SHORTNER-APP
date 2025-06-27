🔐 Authentication
This app uses JWT-based stateless authentication.

📘 Stateful Authentication (Session-based)
Stores session on server.

Requires memory and session management.

⚠️ Users are logged out if the server restarts.

📗 Stateless Authentication (JWT-based)
No session stored on server.

Uses JSON Web Tokens (JWT) to verify user identity.

Token is stored on client-side (e.g., localStorage or cookie).

✅ Better for scaling and performance.

🔑 Note: JWTs are signed with a secret key. Keep the secret key safe and private.

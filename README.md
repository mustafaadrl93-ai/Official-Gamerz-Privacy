# Gamerz | قيمرز — official privacy and legal pages

The public legal-information website for the Gamerz Android gaming community. Only public HTML and the publication workflows belong in this repository; **no private application source, credentials, Firebase data, upload keys or keystore files**.

## Public pages
- [سياسة الخصوصية](./privacy.html) — updated 12 November 2026
- [Privacy Policy](./privacy-en.html) — updated 12 November 2026
- [شروط الاستخدام](./terms.html)
- [Terms of Use](./terms-en.html)
- [حذف الحساب والبيانات / Account deletion](./delete-account.html)

Public URL: https://mustafaadrl93-ai.github.io/Official-Gamerz-Privacy/

## Publication and operational checks
GitHub Pages is configured through the repository's **Publish Gamerz legal website** Actions workflow on pushes to `main`. The publisher should verify that each URL is reachable over HTTPS and displays the newest revision. The website is static and does not take a user's password or identity tokens.

Privacy and external account-deletion requests use the public contact **official.gamerz.app@gmail.com**. The operator must verify that the mailbox receives messages and that account/data deletion requests are processed successfully; this website cannot itself authenticate a user, delete Firestore data, or purge third-party image caches.

The policy accurately describes Firebase, Supabase, historic image providers and data retention. Publication of a policy is not proof that an untested backend deletion worker or regulator-specific requirement has been satisfied. The app's public Data safety declarations must match real behavior.

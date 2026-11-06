# Changes

## 2026-11-07 — Cover creation without sign-in

Removed optional student portal sign-in, password modal, Login/Logout controls, portal profile auto-fill and the unused authentication script. The Student Details card now opens the manual editor for everyone, including keyboard users. Its summary reads only the cover form fields. Existing local cover drafts/presets, course selection, preview and printing remain available; shared legacy portal session storage is neither read nor deleted. About and Privacy text now describe direct entry without an account.

Verification: all seven inline JavaScript blocks across the four HTML pages passed Node syntax checks. Isolated headless Chrome at 390px/1280px verified a clean no-account visit, manual editing, preview/summary updates, keyboard focus, Print button, native PDF rendering, no legacy portal-session reads and no horizontal overflow. External network was blocked; the optional PNG export CDN was not exercised.

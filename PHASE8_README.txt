PRIZEFIGHTER PHASE 8 - PRODUCTION BACKEND + BOXING/BKB ONLY

This phase locks the platform to exactly two combat sport categories:
1. Gloved Boxing
2. Bare Knuckle Boxing (BKB)

Changes made:
- Frontend signup validation rejects all other sports.
- Search/admin wording updated for boxing and BKB only.
- backend/schema.sql now has a sport CHECK constraint.
- backend/production-schema.sql added for a real PostgreSQL deployment.
- backend/server-template.js updated with allowed sport middleware.
- backend/package.json and .env.example added.
- Admin dashboard updated to Phase 8 production backend view.

This ZIP is still runnable as the mobile web demo, but now includes the backend foundation needed to move away from demo storage into a real production backend.

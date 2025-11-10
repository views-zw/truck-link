TruckLink — Full App Scaffold (Expanded)

This scaffold expands the starter into a more complete production-ready structure with:
- Backend: Express + TypeScript + Prisma with RBAC, audit logs, drivers, trucks, trips, admin routes, Socket.IO stub.
- Frontend: React + Vite + Tailwind with passenger, driver, and admin pages (skeletons + working booking flow mock).
- Docker Compose for local dev, .env.example, and seed data.

Run locally (dev):
1. Install Docker and Docker Compose
2. Copy .env.example to .env and set values
3. Run: docker-compose up --build
4. Backend API will be at http://localhost:4000, frontend at http://localhost:3000

This scaffold is a starting point. Review security, secrets, and integrate real payment providers before production.

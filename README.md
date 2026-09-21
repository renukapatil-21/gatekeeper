# gatekeeper
Gateway using Java Spring Boot 

### 3 services created
- Smart Gateway service -> Live traffic
- API management service -> Configurations
- Analytics service -> Observation reporting


### Roles on API management service:
1. Platform Admin
  - Create an organization
  - Create its first administration
  - Activate or suspend it
  - View organizations and infrastructure

2. Tenant Admin
- Login to Gatekeeper Management
- Create and manage routes for exactly one organization
- Configure methods, timeouts, rate limits, idempotency, and header rules

3. Gateway Service
- It can read configuration but cannot change it

# PETIFY Java migration scaffold

This archive preserves the original React/TypeScript source and assets for reference, and adds a Spring Boot + Thymeleaf server-rendered UI under `backend-java`. The current Java API/backend files are retained.

## Run
1. Install JDK 17+ and Maven.
2. Open a terminal in `backend-java`.
3. Run `mvn spring-boot:run`.
4. Open `http://localhost:8080`.

## Important status
This is a first migration scaffold, **not a verified 1:1 conversion**. Landing page styling and original image assets are carried over in a new Thymeleaf page, but the pet catalogue, Supabase authentication, adoption forms, and adopter/shelter/admin dashboard interactions are not yet fully connected to the Java pages. The original React/TypeScript source remains in `src/` and was not deleted, so you can compare or recover the original UI. Do not deploy as production-ready until Maven build, API integration, authentication/authorization, and end-to-end tests pass.

Configure Supabase settings through environment variables; do not commit private keys.

# Docker
## Postgress
- docker run -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres
- docker ps
- docker exec -it dc7f133ab94c /bin/bash
- psql -U postgres
- \dt;
- SELECT * FROM "User";

## Prisma
- npx prisma studio
- npx prisma migrate dev
- npx prisma generate

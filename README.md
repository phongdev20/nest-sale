// setup database
docker compose -p sale-app up -d

nest g resource users --no-spec

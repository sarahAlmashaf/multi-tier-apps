# Use the official PostgreSQL image from Docker Hub
FROM postgres:alpine
 
# Environment variables for PostgreSQL configuration
ENV POSTGRES_USER=salmashaf
ENV POSTGRES_PASSWORD=mypass
ENV POSTGRES_DB=salmashaf-db
ENV POSTGRES_HOST: salmashaf-db-service
ENV POSTGRES_PORT: '5432'
 
# Mount a volume for persistent data storage
VOLUME /var/lib/postgresql/data
 
# Expose the PostgreSQL port
EXPOSE 5432

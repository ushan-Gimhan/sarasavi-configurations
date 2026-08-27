# SARASAVI Configurations

**Author**: S.K.M Ushan Gimhan  
**Student ID**: 241711098  
**Slack Handle**: Ushan Gimhan  
**Module**: ITS 2130 — Enterprise Cloud Architecture  
**GCP Project ID**: `project-af908f5b-1cbf-40dc-9a7`

Centralized external configuration repository for the SARASAVI Bookshop Management System.
Served by Spring Cloud Config Server.

## Files

| File | Service |
|------|---------|
| application.yml | Shared config (all services) |
| api-gateway.yml | API Gateway (:8080) |
| book-inventory-service.yml | Book Inventory (:8081) |
| sales-order-service.yml | Sales Order (:8082) |
| media-service.yml | Media/GCS (:8083) |

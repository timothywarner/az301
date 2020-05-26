# AZ-301 Session 1 Labs

## Design for Identity and Security

* Products
  * B2B / B2C / AADDS
* Authentication
  * App registrations
  * MFA (App Access Panel)
    * Conditional Access / IdP
  * Hybrid Identity (Azure AD Connect)
* Authorization
  * RBAC (AAD and resource)
  * AAD PIM
* Accounting
  * Monitoring AAD
  * Log Analytics
  * Azure Sentinel

## Infrastructure Strategy/Workload Design

* Compute Strategy
  * VM High Availability
    * Availability sets / zones
    * Scale Sets
    * Load balancer / App Gateway
  * Container deployment
    * ACI, ACR, AKS
  * App Service Resiliency
    * Scale out
    * API Management

* Networking Strategy
  * App Service integration
  * Service endpoints/private link

* Monitoring/Consumption Strategy
  * Reservations
  * Spot Instances
  * Dedicated Host
  * Metrics/alerts
  * Log Analytics
  * Consumption/Costing data
  * Tags

## Design a Data Platform Solution (as much as we can)

* Data Management

  * Storage accounts
    * SSE
    * Snapshots
    * Tiering
    * Soft delete
    * VM disks

  * Relational vs non-relational
    * Azure SQL Database
      * Pricing/elastic pools
      * Replication
      * Data protection across lifecycle
    * Cosmos DB
      * Data availability and consistency
      * At-rest data encryption
      * Auditing

  * Data flows
    * Data Lake
    * Data Factory
    * Azure Information Protection
  * Monitoring
    * Metrics Explorer
    * Alerts

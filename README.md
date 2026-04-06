# energy-monitoring-backend
Efficient energy management system tracking sensor data across any energy source. Features real-time data collection, full CRUD for sources/sensors/logs, anomaly detection, and performance analysis via REST API with swagger docs.

** Live Portfolio:** https://lubah-is-hungry.github.io/

## Quick Start 
1. Download `energy-monitoring-complete.zip` & extract to `C:\energy-monitoring\`
2. Open **entire folder** in NetBeans (contains `pom.xml`)
3. MySQL: Execute `rnwdtb.sql` schema
4. Start: Run `EnergyMonitoringApplication.java`
5. Test API: `https://localhost:8080/swagger-ui.html`

## Project Structure (Standard Maven)

energy-monitoring/
├── .mvn/ # Maven Wrapper
├── src/
│ ├── main/java/com/example/energymonitoring/
│ │ ├── controller/ # REST API endpoints
│ │ ├── model/ # JPA Entities
│ │ ├── repository/ # Spring Data JPA
│ │ ├── service/ # Business Logic
│ │ └── EnergyMonitoringApplication.java
│ └── test/java/com/example/energymonitoring/
│ └── EnergyMonitoringApplicationTests.java
├── pom.xml # Maven dependencies
├── mvnw & mvnw.cmd # Maven Wrapper (no install needed)
└── rnwdtb.sql # MySQL schema

## Features 
- Real-time sensor data ingestion & storage
- Complete CRUD operations
- Anomaly detection analytics
- Swagger Rest API documentation
- Clean Layered architecture

## Tech Stack
|   Backend   | Database | Build |      API     |
|-------------|----------|-------|--------------|
| Spring Boot |   MySQL  | Maven | REST/Swagger | 

** Results:** Optimized oindexes -> ** 25 % faster queries**
## Files 
- - `energy-monitoring-complete.zip` - Complete Maven project
- `rnwdtb.sql` - MySQL schema

## Linux Performance Engineering
**CLI toolkit for Java/Spring Boot analysis:** 

top/htop # CPU/memory profiling
iostat -x # MySQL I/O bottlenecks
ss -s # Network connections
vmstat 1 # System resource analysis

**Applied:** Indexing optimizations → **Production-ready performance**


[lubah-is-hungry@github](mailto:lubah-is-hungry@github.com)


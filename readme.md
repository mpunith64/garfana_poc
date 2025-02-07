# Grafana Monitoring Setup

## Overview
This repository contains the configuration for setting up Grafana, Prometheus, and Windows Exporter using Docker Compose. The services are configured to monitor system metrics efficiently.

## Features
- **Grafana**: Data visualization and monitoring dashboard.
- **Prometheus**: Metrics collection and querying.
- **Windows Exporter**: Collects Windows system metrics.

## Prerequisites
- Docker & Docker Compose installed.
- Windows Exporter installed and running.

## Setup Instructions
1. Clone the repository.
2. Configure Prometheus to scrape metrics from Windows Exporter.
3. Start services using Docker Compose.
4. Access Grafana at `http://localhost:3000`.
5. Configure Prometheus as a data source in Grafana.

## Usage
- View system metrics in Grafana dashboards.
- Modify configurations to monitor additional services.

## Contribution
Feel free to submit issues and pull requests to improve the setup.


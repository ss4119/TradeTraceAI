# TradeTraceAI

## Work in Progress

A platform for analyzing financial documents to detect insider trading patterns and compliance violations.

## Overview

TradeTraceAI processes financial documents like PDFs and spreadsheets, then uses machine learning to spot potential compliance issues and suspicious trading activity. Users upload documents, get analysis results, and can generate reports.

## Features

- Document upload and parsing (PDF, Excel, CSV)
- ML-powered analysis using FinBERT models
- Real-time dashboard with results and Grafana monitoring
- Risk scoring and categorization
- Compliance report generation
- User authentication and management

## Tech Stack

**Frontend:** Next.js, React, TypeScript
**Backend:** Spring Boot (Java), FastAPI (Python)  
**Database:** PostgreSQL, Supabase
**ML:** FinBERT, Transformers
**Monitoring:** Grafana
**Other:** WebSocket, Redis

## Architecture

Microservices setup with Java handling file processing, Python running ML analysis, Next.js for the UI, and PostgreSQL for data storage. Redis for caching and WebSocket for real-time updates.

Still working on completing core features and deployment.
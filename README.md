# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69b3c29a83597f01dd921f95_user:okmTPk0uptWY%26k6%23Fij4YsperP%40nBt10@ep-super-haze-adlwwlem.c-2.us-east-1.aws.neon.tech:5432/AppDB_69b3c29a83597f01dd921f95?sslmode=require`

**Swagger API Tester URL:** /swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.

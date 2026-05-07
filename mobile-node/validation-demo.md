# Mobile Node Validation Demo

This document demonstrates the first prototype logic for GENCROP mobile node validation.

## Input Data

- Crop image
- Seed variety
- Soil metadata
- Region data
- Farmer-submitted observation

## Local AI Validation

The mobile node analyzes submitted agricultural data locally before blockchain submission.

## Validation Output

```json
{
  "crop_detected": "Heirloom Tomato",
  "soil_quality": "high",
  "data_quality_score": 92,
  "ai_status": "verified",
  "passport_ready": true
}

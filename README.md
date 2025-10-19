# SLU Food Finder


<img width="327" height="645" alt="Screenshot 2025-10-19 at 6 06 57 AM" src="https://github.com/user-attachments/assets/67b56701-c0aa-4614-997e-f35c2fa02601" />

# SLU Food Finder

A minimal, Apple-inspired food discovery app for Amazon employees in South Lake Union, Seattle.

## Overview

Clean, interactive map app for finding lunch spots near Amazon SLU buildings. Built with React Native/Expo, featuring OpenStreetMap integration, real-time search, and multi-dimensional restaurant filtering.

## Features

- **Interactive Map**: Pan/zoom with OpenStreetMap (Leaflet on web, react-native-maps on native)
- **Visual Markers**: Emoji-based restaurant icons for instant recognition
- **Smart Search**: Real-time filtering by name, cuisine, or address
- **Multi-Filter System**: 
  - Price ($-$$$)
  - Rating (4.0+, 4.5+)
  - Smell Rating (4.5+, 4.8+) 👃
  - Food Quality (4.5+, 4.7+) 👨‍🍳
- **Smooth UX**: Spring animations, haptic feedback, swipe gestures
- **Apple Design**: Monochromatic palette, SF-style typography, generous white space



## Data Model

Each restaurant includes: name, cuisine, coordinates, price level, rating, smell rating, food quality, emoji logo, website.

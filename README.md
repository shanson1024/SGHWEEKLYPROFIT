# Deployment Documentation

## Overview
This document outlines the steps to deploy the SGHWEEKLYPROFIT application.

## Prerequisites
- Ensure you have the latest version of Node.js installed.
- Have access to the production server.
- Ensure database configurations are in place.

## Deployment Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/shanson1024/SGHWEEKLYPROFIT.git
   cd SGHWEEKLYPROFIT
   ```
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Build the application**:
   ```bash
   npm run build
   ```
4. **Deploy to server**:
   - Use your preferred method (e.g., scp, rsync) to transfer files to your server.
5. **Start the application**:
   ```bash
   npm start
   ```

## Rollback Instructions
In case of a fault, revert to a previous version by:
1. Stopping the application.
2. Reverting to the previous build on the server.
3. Starting the application again.

For any issues during deployment, please contact the development team.
# Plaud Developer Documentation

This repository contains the official developer documentation for Plaud.ai's API and developer platform. The documentation is built using [Mintlify](https://mintlify.com/), a modern documentation platform.

## Overview

Plaud.ai provides industry-leading AI recording hardware and a powerful developer platform. This documentation helps developers integrate with Plaud's API to access recordings, transcriptions, and AI-generated summaries.

## Documentation Structure

- **Getting Started**
  - Introduction - Overview of the Plaud Developer Platform
  - Quickstart - Get up and running with the Plaud API

- **Feature Guides**
  - Guides Overview - Comprehensive overview of available features
  - Device Management - Managing Plaud recording devices
  - User & Tenant Management - Organizing users and tenants
  - File Management - Working with recordings and files

- **API Reference**
  - Complete OpenAPI specification for all endpoints

## Local Development

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Install Mintlify CLI:
   ```bash
   npm install -g mintlify
   ```

2. Clone this repository:
   ```bash
   git clone <repository-url>
   cd plaud-dev-docs
   ```

3. Start the development server:
   ```bash
   mintlify dev
   ```

4. Open your browser and navigate to `http://localhost:3000`

### Making Changes

- Edit Markdown files (`.mdx`) in the repository to update content
- Update `docs.json` to configure navigation and settings
- Custom styles can be found in `styles/custom.css`

## Deployment

The documentation is automatically deployed when changes are pushed to the main branch. The deployment process is handled by Mintlify's CI/CD pipeline.

## File Structure

```
plaud-dev-docs/
├── api-reference/
│   └── openapi.json         # API specification
├── guides/
│   ├── device-management.mdx
│   ├── file-management.mdx
│   └── user-management.mdx
├── images/                  # Images for the documentation
├── logo/                    # Logo files
├── styles/
│   └── custom.css           # Custom styling
├── docs.json                # Configuration file
├── favicon.svg              # Site favicon
├── guides-overview.mdx
├── introduction.mdx
├── quickstart.mdx
└── README.md                # This file
```

## Contributing

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes
4. Submit a pull request

## Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [Plaud Developer Community](https://community.plaud.ai)
- [Contact Support](mailto:dev-support@plaud.ai) 
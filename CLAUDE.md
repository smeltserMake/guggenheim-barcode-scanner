# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Context
This is a **sales opportunity project** for Guggenheim Partners. The focus is exclusively on building HTML-based web applications to demonstrate Make.com's capabilities and value proposition.

## Current Solution: Barcode Scanner Demo
- **File**: `barcode-scanner.html`
- **Purpose**: Demonstrate Make.com webhook integration through a practical barcode scanning use case
- **Key Features**:
  - Camera-based barcode scanning (ZXing library)
  - Geolocation capture
  - Direct webhook integration to Make.com
  - Mobile-responsive, no app installation required

## Development Guidelines
1. **HTML-Only Focus**: All solutions should be self-contained HTML files with inline CSS/JavaScript
2. **Make.com Integration**: Always include webhook endpoints to showcase automation potential
3. **Enterprise Features**: Include elements like location tracking, device info, audit trails
4. **Mobile-First**: Ensure all demos work seamlessly on mobile devices

## Make.com Webhook
Current webhook endpoint: `https://hook.us1.make.com/vrkgwj79n3ak7kwrp07m1x0jnjbpsjtx`

## Sales Engineering Notes
- This is a pre-sales technical demonstration
- Focus on showing how easily Make.com integrates with custom solutions
- Emphasize no-code/low-code backend automation capabilities
- Highlight enterprise use cases: inventory tracking, asset management, field operations
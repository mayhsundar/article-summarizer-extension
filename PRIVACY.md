# Privacy Policy for Briefly

**Last Updated: January 9, 2026**

## Overview

Briefly ("the Extension") is committed to protecting your privacy. This privacy policy explains how we handle your data when you use our Chrome extension.

## Data Collection

### What We Collect

The Extension requires users to provide their own API keys for:
- **Groq API** (for AI summarization)
- **Google Gemini API** (alternative AI summarization provider)
- **Google Translate API** (for translation features)

These API keys are stored locally in your browser using Chrome's storage API and are never transmitted to our servers.

### What We Don't Collect

- We do **NOT** collect, store, or transmit any personal information
- We do **NOT** track your browsing history
- We do **NOT** collect analytics or usage statistics
- We do **NOT** have access to your API keys or any data you process

## Data Usage

### How Data is Processed

When you use the Extension:
1. The Extension extracts article content from the current web page you're viewing
2. Article content is sent directly to your chosen AI provider (Groq or Google Gemini) using **your own API key**
3. The summarized content is displayed directly to you
4. No data is sent to any third-party servers except the AI providers you choose to use

### Local Storage

The Extension stores the following data locally on your device:
- Your API keys (Groq, Gemini, Google Translate)
- Your language preferences
- Extension settings and preferences

This data remains on your device and is never transmitted to us.

## Third-Party Services

The Extension integrates with the following third-party services:

### Groq API
- **Purpose**: AI-powered article summarization
- **Data Shared**: Article content you choose to summarize
- **Privacy Policy**: [https://groq.com/privacy-policy/](https://groq.com/privacy-policy/)

### Google Gemini API
- **Purpose**: Alternative AI-powered article summarization
- **Data Shared**: Article content you choose to summarize
- **Privacy Policy**: [https://policies.google.com/privacy](https://policies.google.com/privacy)

### Google Translate API
- **Purpose**: Translation of summaries
- **Data Shared**: Summarized text you choose to translate
- **Privacy Policy**: [https://policies.google.com/privacy](https://policies.google.com/privacy)

**Important**: Your use of these services is subject to their respective privacy policies and terms of service. We recommend reviewing their policies before using the Extension.

## Permissions

The Extension requires the following Chrome permissions:

- **activeTab**: To access and read the content of the current tab for summarization
- **storage**: To save your API keys and preferences locally
- **host_permissions**: To communicate with Groq API, Google Gemini API, and Google Translate API

## Data Security

- All API keys are stored locally using Chrome's secure storage API
- The Extension uses HTTPS for all API communications
- We do not have access to your API keys or any data processed by the Extension

## Your Control

You have complete control over your data:
- You can remove your API keys at any time through the Extension settings
- You can uninstall the Extension at any time, which will delete all locally stored data
- You can review and modify all Extension settings in the options page

## Children's Privacy

The Extension is not directed at children under the age of 13, and we do not knowingly collect any information from children.

## Changes to This Privacy Policy

We may update this privacy policy from time to time. Any changes will be reflected in the "Last Updated" date at the top of this policy. We encourage you to review this policy periodically.

## Open Source

This Extension is open source. You can review the complete source code at:
[https://github.com/mayhsundar/briefly](https://github.com/mayhsundar/briefly)

## Contact

If you have any questions or concerns about this privacy policy, please contact us by opening an issue on our GitHub repository:
[https://github.com/mayhsundar/briefly/issues](https://github.com/mayhsundar/briefly/issues)

## Compliance

This Extension complies with:
- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)

## Summary

In short:
- ✅ Your API keys are stored locally and securely
- ✅ No personal data is collected or transmitted to us
- ✅ Article content is only sent to AI providers using your own API keys
- ✅ You have full control over your data
- ✅ The Extension is open source and transparent

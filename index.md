# StylePeekr Privacy Policy
Last Updated: [29/03/2024]

## Overview
StylePeekr is a Chrome extension that allows web designers and developers to inspect CSS styles, extract color palettes, and view page assets. This privacy policy explains how StylePeekr handles user data.

## Data Collection
StylePeekr is designed with your privacy as a priority. The extension does not collect or store any personal data, browsing history, or other sensitive information.

## How StylePeekr Works
StylePeekr processes website content (CSS styles, colors, and assets) entirely locally within your browser. This processing is necessary to provide the core functionality of the extension:

- Element inspection and style analysis
- Color palette extraction
- Asset identification and download

All operations are performed locally within your browser. No data is sent to external servers except for downloading assets that are already referenced on the webpage being analyzed.

## Permissions Used
StylePeekr requires minimal permissions to function:

- `activeTab`: Allows StylePeekr to function only on the tab you're currently viewing, and only when you activate the extension.
- Content script host permissions: Required to inject the inspection interface and analyze page styles. This is implemented through the manifest's content_scripts and web_accessible_resources sections, which are necessary for core functionality.

## Website Content Access
StylePeekr only accesses and processes:
- CSS styles and computed properties
- Color values used in the webpage
- Images and other media assets that are already present on the page
- Text content related to style information

All processing is done locally within your browser, and no content is transmitted to external servers except when downloading assets that are already part of the webpage being analyzed.

## Third-Party Libraries
StylePeekr uses JSZip (version 3.10.1) as a bundled library to create ZIP archives when users choose to download multiple assets. This library is included in the extension package and does not make external connections.

## Future Updates
In future versions, StylePeekr may collect anonymous, non-identifying usage statistics such as browser version, platform information, and feature usage patterns to help improve the extension. This would only be implemented with clear user notification and consent, and would never include personal data, browsing history, or website content.

## Contact Information
If you have any questions about this privacy policy or StylePeekr's data practices, please contact us at [stylepeekr@gmail.com].

## Changes to This Policy
We may update this privacy policy from time to time. We will notify users of any changes by updating the "Last Updated" date at the top of this policy.

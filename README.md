# Ninetailed API Google Tag Manager (GTM) template
A Google Tag Manager customer template for firing Ninetailed API calls.

## Details
This template lets you fire either a `track` or `identify` call to the Ninetailed endpoint.

## Usage
Documentation for setup and usage is available on [docs.ninetailed.io](https://docs.ninetailed.io/integrations/getting-started).

## Instructions for testing
1. Download the `template.tpl` file from this repo.
2. Browse to a [Google Tag Manager](https://tagmanager.google.com/) web container with which you want to test the template.
3. In the container, browse to **Templates** by clicking the respective link in the left-hand side navigation.
4. In the box labelled **Tag Templates**, click the **New** button.
5. In the template editor, click the overflow menu (the three-dot menu in the top right corner), and choose **Import**.
6. Select the `template.tpl` file and click to proceed.
7. Wait for the template to finish importing. Once done, click **Save** and close the editor.

## Release notes
| Date | Notes |
|------|-------|
| 07 August 2024 | Change userID to text field. Improve field descriptions. Prevent empty event name. Add debug logs. Add tests. |
| 12 February 2024 | Remove object-action support. |
| 25 August 2022 | First version of the template released. |
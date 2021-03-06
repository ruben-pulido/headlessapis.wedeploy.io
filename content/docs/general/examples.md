---
mainPage: false
title: Examples
description: Examples with Liferay Headless APIs
weight: 1
---

## Examples

* [Root Endpoint](https://documenter.getpostman.com/view/6029310/RznCpeaX)
* [Content Space Endpoint](https://documenter.getpostman.com/view/6060345/RznBPgKy)
* [Content Structures](https://documenter.getpostman.com/view/6060345/RznCpeet)
* [Blogs Endpoint](https://documenter.getpostman.com/view/6033677/RznCpeaY)
* [Structured Content Endpoint](https://documenter.getpostman.com/view/6060345/RznBPg2G)

## Advanced Examples with Postman

These examples can be executed using [Postman](https://www.getpostman.com/).

### Prepare Your Environment

Before executing the examples, you must follow these steps: 

- Import the demo data included in [this repository](https://github.com/liferay-labs/headless-apio-demo).
- Configure the [Postman environment](https://learning.getpostman.com/docs/postman/environments_and_globals/manage_environments/) with these variables (it is important to notice that the value should be set as `CURRENT VALUE` no `INITIAL VALUE`):

| Variable               | Description                                                                  |
|------------------------|------------------------------------------------------------------------------|
| `username`             | Your Liferay username (e.g., test@liferay.com)                               |
| `password`             | Your Liferay password (e.g., test)                                           |
| `contentSpaceId`       | The ID of your content space/site. Send a request to the [`content-spaces` endpoint](/docs/content-space/index.html) to get a list of your available content spaces and their IDs. |
| `folderId`             | The folder's ID. Send a request to the [`folder` endpoint](/docs/content-space/documents-repository/folders/index.html) to get a list of your available folders and their IDs. |
| `roleId`               | The role's ID. Send a request to the [`roles` endpoint](/docs/roles/index.html) to get a list of your available roles and their IDs. |
| `userId`               | The user's ID. Send a request to the [`user-account` endpoint](/docs/user-account/index.html) to get a list of your available users and their IDs. |
| `organizationId`       | The organization's ID. Send a request to the [`organization` endpoint](/docs/organization/index.html) to get a list of your available organizations and their IDs. |
| `structuredContentId`  | The structured content's ID. Send a request to the [`structured-contents` endpoint](/docs/content-space/structuredContents/index.html) to get a list of your available structured contents and their IDs. |
| `eventResultStructureId` | The ID of the event result in the content structure. Send a request to the [`content-structures` endpoint](/docs/content-structure/index.html) to get a list of your available event results (`Event Result`) and their IDs. |
| `formId`                 | The form's ID. | 

### Postman Collections

* Root Endpoint [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/4eaef9d6ba43fe179a15)

* My User Account [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/d0d8c0f27a04d22ba3f7)

* Content Spaces [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/625390af8a347edae5c9)

* Documents Repository [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/d3e58a5899c098a21ebb)

* Content Structures [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/203e52fd8ab013b9273d)

* Folders [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/dce4a5ad7b52311b5fb3)

* Structured Content [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/fd09da20da25956af16e)

* Workflow [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/ff849ad861374e6676c3)

* Blog Postings [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/323d7a1b588133b01b5d)

# sharepoint-overrides
3 `CSS` files to make SharePoint 2013 behave, visually

- `_sharepoint-all-users.scss` contains overrides for all users (logged in or not). It is a `SCSS` partial to be imported into your main Sass setup.
- `sharepoint-cms` contains overrides for logged in general CMS users. To be compiled separately and included conditionally.
- `sharepoint-cms-edit` contains overrides for logged in CMS users editing documents. To be compiled separately and included conditionally.
---
title: talk-plugin-facebook-auth
permalink: /plugin/talk-plugin-facebook-auth/
layout: plugin
plugin:
    name: talk-plugin-facebook-auth
    depends:
        - name: talk-plugin-auth
    provides:
        - Server
        - Client
---

Enables sign-in via Facebook via the server side passport middleware.

Configuration:

- `TALK_FACEBOOK_APP_ID` (**required**) - The Facebook App ID for your Facebook
  Login enabled app. You can learn more about getting a Facebook App ID at the
  [Facebook Developers Portal](https://developers.facebook.com) or by visiting
  the [Creating an App ID](https://developers.facebook.com/docs/apps/register)
  guide. This is only required while the `talk-plugin-facebook-auth` plugin is
  enabled.
- `TALK_FACEBOOK_APP_SECRET` (**required**) - The Facebook App Secret for your
  Facebook Login enabled app. You can learn more about getting a Facebook App
  Secret at the [Facebook Developers Portal](https://developers.facebook.com)
  or by visiting the
  [Creating an App ID](https://developers.facebook.com/docs/apps/register)
  guide. This is only required while the `talk-plugin-facebook-auth` plugin is
  enabled.

_NOTE: FabceBook auth requires your site to use `https` (SSL) not `http`. If your site is not `https` you can not use this plugin!_

## GDPR Compliance

In order to facilitate compliance with the
[EU General Data Protection Regulation (GDPR)](https://www.eugdpr.org/), you
should review our [GDPR Compliance](/talk/integrating/gdpr/) guidelines.

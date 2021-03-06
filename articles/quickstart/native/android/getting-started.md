---
title: Getting started
description: Short Introduction to the Auth0 Android Quickstarts.
budicon: 715
---

This multistep quickstart guide will walk you through managing authentication in your android apps with Auth0.

## Sample Projects

Each tutorial in the series includes a link to its corresponding sample project. You can find all the samples [here](https://github.com/auth0-samples/auth0-android-sample).

## Dependencies

Each tutorial will require you to use either [Auth0.Android](https://github.com/auth0/Auth0.Android) or the [Lock](https://github.com/auth0/Lock.Android) library.

- [Auth0.Android](https://github.com/auth0/Auth0.Android) is a toolkit that lets you communicate with many of the basic [Auth0 API](https://auth0.com/docs/api) functions in a neat way.
- [Lock](https://github.com/auth0/Lock.Android) is an `Activity` that is easy to present in your app. It contains default templates (that can be customized) for login with email/password, sign up, social providers integration, and also password recovery.

The `Lock` dependency is already integrated in each sample project through [Gradle](https://gradle.org/).
`Lock` packs most of the `Auth0.Android` functionality inside.

## Create a Client

If you haven't already done so, create a new client application in your [Auth0 dashboard](${manage_url}/#/applications/${account.clientId}/settings) and choose **Native** for the Type.

![App Dashboard](/media/articles/angularjs/app_dashboard.png)

<%= include('_includes/_callback_urls') %>

<%= include('_includes/_credentials') %>

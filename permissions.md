# Permissions - GPS, Notification

* Decisiders : Thuy My Lam, Sanghyeon Lee
* Date : 02-21-2024

## Status
Proposed

## Context
[GPS](https://support.google.com/accounts/answer/6179507?hl=en)
In order to provide available restaurants based on the user's current location, permission to use GPS should be granted."

[Notification](https://support.google.com/chrome/answer/3220216?hl=en&co=GENIE.Platform%3DDesktop)
Users can receive notifications about the current status of their order.

## Decision
GPS, Notification

## Consequences
- By accessing the current location of the user, our application will provide restaurants nearby the user. Users do not have to manually select their location.
- The application displays the real-time order status, allowing users to track the delivery process.
- The application sends notifications for various stages of the order process, including "Order accepted," "Remaining time to be cooked," "Food is picked up," and "Food is delivered."
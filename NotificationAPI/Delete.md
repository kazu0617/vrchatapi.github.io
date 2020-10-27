# Delete Notification

!> We tried to test these APIs and we are not sure how they work in-game, even friendrequest wasn't recieved unless we sent a real friend request and not a notification. will have to do some further testing.

This API allows you to delete a notification

The endpoint can suggest that the notification still exists, but it will just be hidden, but we can't get these notifications using the `hidden` notification type when filtering.

## Request Method
PUT

## Endpoint
https://api.vrchat.cloud/api/1/auth/user/notifications/[ID]/hide

id - the notification id

## Requires Authentication
Yes (See [here](Authorization.md) for details)

## Returns

[`Notification object`](Objects/Notification?id=notification-object)

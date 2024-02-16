Bot gestione insta
Nome: QInsta - Pintescul studios
Grafica: PyQt6
Libreria API: Instagrapi

Functionality

* Load and save user lists in the UI, combine lists in new grouped lists
* Load and save account lists in the UI, combine account lists in new grouped lists
* Load and save settings in the UI, settings will be
    1. Send message and/or comment on nth post (0 the first, -1 the last, a range can be also chosen) ({username}, {name}, {followers}, {followings}, {media_count} will be formatted to their respective value), messages or comments can be multiple, the user will be able to add a message or comment to the list and optionally specify under what condition to send that message, a message could be sent by responding to a story,  conditionals shall be:
        * Only if the user has some keywords in the biography (at least one or half or all of them)
        * follower count is more or less than x
        * different ratios more than or less than x
    2. Send likes to nth post or range of posts, including stories (either one or all)
    3. Save nth post or range of posts
    4. Post some media to either feed (normal,reel) or story
    5. Download nth media or story or download only if the user has some keywords in the description, selection will be: at least one keyword, at least half keywords, all keywords, or even download if ratios or like count is more than x
    6. Save login information and device info for quick re-login
    7. Pre-sending activities such as exploring feed, exploring reels, searching hashtags etc
    8. Fetch list of users from hashtags, user followers, followings, user nth post likes, link to media (like or comment list)
    9. Save user data (such as username, userID, user nickname, follower count, following count, media count)
* Save logs for easy reading as a folder (content will be: MESSAGES.XLSX, COMMENTS.XLSX, LIKES.XLSX, SAVES.XLSX, MEDIA_UPLOADS.XLSX, ACCOUNT.XLSX)
* Load logs to get an overview over what happened with graphs, which account sent more

Developement

* the project will be saved on GitHub as a a private repository
* The UI will be open source

Personal (Free):
Load and save user lists in the UI.
Load and save account lists in the UI.
Load and save basic settings.
Send likes to nth post.
Save nth post.
Download nth media or story.
Save login information.
Send messages to 50 users daily (single message per user).

Starter:
All Personal tier features.
Combine lists in new grouped lists.
Combine account lists in new grouped lists.
Send likes to a range of posts.
Post media to the feed or story.
Send messages and comments to 500 users daily (up to 5 messages per user).
Save login cookies.

Balanced:
All Starter tier features.
Send messages, comments, and likes to 5000 users daily (infinite messages and comments).
Send profiles, posts, and reels.
Save login cookies.
Save logs (messages, comments, likes, saves, media uploads, account).

Advanced:
All Balanced tier features.
Post media to story or feed/reels.
Save login cookies and device info.
Proxy support.
Send messages, comments, and likes to 10,000 users daily (infinite messages and comments).
Fetch likes on nth post.
Download media with advanced conditions (ratios, like count).

Professional:
All Advanced tier features.
Send messages, comments, and likes to 1 million users daily (infinite messages and comments).
Send profiles, posts, reels, and stories.
Post media to story or feed/reels.
Up to two parallel accounts.
Save login cookies and device info.
Save sending data logs.
Proxy support.
First-line support calls.

Enterprise:
All Professional tier features.
Infinite accounts.
Every feature unlocked to its maximum.
Save data logs to excel.
Proxy and AWS EC2 support.
First-line support calls.

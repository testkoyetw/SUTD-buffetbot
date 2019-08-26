# SUTD-buffetbot

Official DSBJ bot. Looking for people in the school mailing list with access to regular event advertisements (and wish to continue the development) to keep the bot running. Contact me if you are interested.

Code to be updated.

## Possible To Do List

- Update to use the new [Java library](https://github.com/rubenlagus/TelegramBots ). Current version used is pretty outdated.
- Synchronize update & feedbacks. No synchronization is done now and will break if someone sends a feedback while the system updates (current hack is to do an update when no one is awake).
- Replace current image recognition API (currently Baidu, don't work well sometimes) to pick up texts in image attachments. Some fixes needed e.g. convert 'o' to '0'. 
- Update the list of school locations used for regex.
- Allow for update of buffet information manually through telegram to fix things in case.
- Use the school website's calendars to get additional event information. For all pillars and some research centers they have calendars for all their events (although not always updated).
- Add a block user function.
- Keep a list of known event types, their duration (as some events only provide the starting time) and buffet availability (and if buffet is provided at the start or end of the event) so that only events with buffet are logged.

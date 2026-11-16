# Sweater Countdown Lock Screen

## How It Works
Six iPhone Shortcuts automations, one per milestone date. Each runs at
6:00 AM on its date and sets that milestone's image as the lock screen.
The wallpaper always matches the current milestone, even if I skip a day.

Each image shows the milestone title, T-minus days to the Nov 30 deadline,
a progress graphic, and planning notes.

| Date | T-Minus | Milestone |
|---|---|---|
| Fri, Nov 13 | T-17 | Finish second front panel |
| Mon, Nov 16 | T-14 | One sleeve down |
| Thu, Nov 19 | T-11 | Finish both sleeves |
| Sat, Nov 21 | T-9 | Seam entire body |
| Tue, Nov 24 | T-6 | Complete ribbing and buttons |
| Wed, Nov 25 | T-5 | Wet-block sweater to dry |
| Mon, Nov 30 | T-0 | Mail finished gift |

## Setup
1. Download the album to your iPhone. Name the photos 01 to 07 in
   milestone order.
2. Open Shortcuts > Automation > + and choose Time of Day.
3. Set the time to 6:00 AM, Repeat to Monthly, and pick the milestone's
   day (13, 19, 21, 24, 25, or 30).
4. Add Find Photos (Album is the milestone album, Title is that photo,
   Limit 1).
5. Add Set Wallpaper with that photo as input. Turn Show Preview off.
6. Choose Run Immediately and turn Notify When Run off.
7. Repeat steps 2-6 for all seven dates.
8. Run the most recent milestone's shortcut manually to set the current
   image.

## Notes
- Requires the Set Wallpaper action in Shortcuts. Tested on iOS 26.
- Automations repeat monthly. Delete all seven after Nov 30.
- To fix a missed day, run that milestone's shortcut manually.

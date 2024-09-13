# TODOS

## Basic

- Implement settings functionality for constant checks for bookmark updates (incl. radio button)
  - just figure out how to do the checkboxes/radio buttons in the settings at all
- Reenable save buttons on your own history at least
  - This will take slightly more logic for choosing when addSaveButtons gets triggered, but shouldn't be overly complicated
- Test on mobile, test logged out, test pages more
- Test failing bookmark update requests?
- There are some pages that bookmarks don't appear - note and fix those

## Maybe nice to have

- Pick whether you want save buttons on your own work pages
- Better status updates for when bookmark list update is running/finished
  - Possibly a flash notice once it finishes? Clearer alerts for user at least
- Figure out how to handle bookmark deletions without scrapping the whole list and starting again
  - if you do figure it out, may require more of a full list object to be able to remove specific items from the middle
  - just have an object with keys and values? but I'm relying on the orderedness of arrays
- Make more cool settings
- Try putting an x button on the settings like on the bookmark form for close

## Prettifying

- Give the bookmark form a shadow
  - It's styled like the original AO3 one if you add "new dynamic" to the classes, but it also renders _on top of_ other works, so that's why we're not doing that
    - An idea was to make something inside the outside div have it to see if it wouldn't overflow then

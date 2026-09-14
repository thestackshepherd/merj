# Nexcal.dev
nexcal.dev — a calendar consolidation and translation layer. 
It pulls events from any number of scattered sources 
(ICS feeds, computed generators, scraped schedules) 
into one normalized store, then serves
out in whatever shape you need

a merged .ics feed, a filtered subset, 
JSON/CSV for reporting, a Slack/Teams notification, or a queryable freebusy window. 
It doesn't replace your calendar app — 
it sits underneath the ones you already use, doing the unglamorous work of reconciling formats, 
deduping overlapping events, and re-exposing everything as clean, subscribable output.
# My LittleLink Fork
This is a custom fork of LittleLink, by Seth Cottle https://github.com/sethcottle/littlelink. The biggest changes are simply some light adjustemtns to a few brand CSS styles, and the re-organization of the links I used in a personal-preference sort order, instead of the default alphabetical.

# Maintenance
When needed, I occasionally sync my fork from the upstream to bring in additional site support or code changes that have been added. Aside from desired "new" platform support however, my upstream syncs are few and far between, since this site is SO lightweight, it does not require a lot of updates.

Some basic GH automations are setup by me, primarily around linting, link validations, and typo checking just to make sure things don't slip through the cracks.

# Deployment
My repo is synced to CloudFlare Pages, and is automatically updated anytime `main` is updated via workers on the CloudFlare side that monitor the repo for changes, vs having to run GH automations.

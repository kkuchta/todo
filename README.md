# README

This project is really just an excuse to put together a bunch of technologies I've used in the past, but never all together.  It's what I would do if I were starting a new web app from scratch that I expected to be working on for a few years and where I didn't have any specific requirements that dictated something different.  This grew out of me realizing I haven't actually spun up a new full stack project in a while and the tools I like for that have changed since the last time I did.

The end goal here is a minimal-logic app (probably just a todo list) with the following tech choices:

- Backend
	- Postgres
	- Rails
		- Auth framework TBD.  It Authlogic still good?
	- Graphql API
- Frontend
	- Typescript
	- React
	- Apollo graphql client lib
	- Packaging TBD: Gulp + webpack, I guess?  Gotta see what the state of the art is here.
- Test/Lint/CI
	- StandardRuby linting
	- StandardJS linting if I can get that working with typescript
	- CircleCi or something equivalent
    - Storybook + chromatic

If I'm not bored by the end of all that, I'll probably play around with client-side state management patterns + libs.  So far all I've used is "nothing, plus a lot of prop tunneling", "redux", and some context stuff someone else set up, so I need to do some exploration there.

This is obviously overkill for a todo app.  It's an exercise, not a statement about what's appropriate for an app of this complexity.  :)
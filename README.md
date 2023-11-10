# qwk

qwk is under construction. It might eventually be a modal text editor.
Right now, it's a hobby project and an excuse to learn a modern system
programming language.

## The idea

I'd like to create a text editing "engine" that listens for abstract
text editing "events" and either edits a "buffer" (an in-memory file
being edited) or emits abstract "instructions" for the "front end" of
the text editor to execute. As much as possible I'd like the front end
to be decoupled from the engine.

## The plan

The plan is to implement at least one prototype in Python before
implementing a prototype in a system programming language. I want to
move quickly and figure out what parts are going to be especially
tricky.

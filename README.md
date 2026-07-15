# LoopGolf for Claude Code

Live golf tee time availability across US golf courses, inside Claude Code.

Connects Claude to LoopGolf's free public MCP server (`co.loopgolf/tee-times` in the
official MCP Registry). Read-only, no API key.

## Install

    /plugin marketplace add matthew-holder/loopgolf-claude-plugin
    /plugin install loopgolf@loopgolf

## Tools

- **search_tee_times** — live, bookable tee times near a US city or zip; filter by
  date, players, time of day, max price, holes, and hot deals.
- **get_course_tee_times** — every open time at a specific course, with
  availability by date.

Ask: *"find me a tee time near Phoenix Saturday morning under $60."*

Booking links go to [loopgolf.co](https://www.loopgolf.co). Questions:
caddyshack@loopgolf.co · Docs: https://www.loopgolf.co/ai

# Standard Operating Procedures

## Quick Links

### Meetings
- Meeting Calendar: [Google Calendar](https://calendar.google.com/calendar/u/0?cid=ZW1haWxAZ2V0b2RrLm9yZw), [iCal](https://calendar.google.com/calendar/ical/email%40getodk.org/public/basic.ics), [Web](https://calendar.google.com/calendar/embed?src=email%40getodk.org&ctz=America%2FLos_Angeles)
- [Meeting Agendas and Minutes](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA/edit)
- [Zoom Meeting Room](https://us06web.zoom.us/j/84959312841?pwd=eEt3a2tKMy9sZG5zQXZBRzhFVThzUT09)

### Product
- [Roadmap](https://github.com/getodk/roadmap/projects/1)
- ODK Repos: [Collect](https://github.com/getodk/collect), [Central](https://github.com/getodk/central), [Docs](https://github.com/getodk/docs), [ODK XForms](https://github.com/getodk/xforms-spec)
- Ecosystem Repos: [XLSForm](https://github.com/xlsform), [Enketo](https://github.com/enketo)

### Governance
- [TAB Members](https://getodk.org/about/ecosystem.html)
- [TAB Governance](https://github.com/getodk/governance/blob/master/TAB-GOVERNANCE.md)
- [Tool Governance](https://github.com/getodk/governance/blob/master/TOOL-GOVERNANCE.md)

### Other
- [Meeting Facilitator Checklist](#meeting-facilitator-checklist)
- [Meeting History](https://docs.google.com/spreadsheets/d/1xD44Km1p0LXoIjBkGxolPvkhq7OXlxA28CN2LKrsT2A/edit#gid=0)
- [TAB Parking Lot](https://docs.google.com/spreadsheets/d/1_vEWH9OFibkC2DuTe7nfy37SgEVLDFI8stGdZKDE5AE/edit#gid=0)
- [TAB Forum Category](https://forum.getodk.org/c/governance/tab)
- [TAB Forum Tag](https://forum.getodk.org/tags/tab)

For more details on the TAB's responsibilities, see the [TAB governance](https://github.com/getodk/governance/blob/master/TAB-GOVERNANCE.md) approved on Nov 7, 2017.

## Communications

The TAB engages in various sorts of communication with different audiences. Is it important to understand which communication channel is appropriate for which message.

| Venue | Channel | Visibility | Purpose |
|---|---|---|---|
| Zoom | [Meeting Room](https://us06web.zoom.us/j/84959312841?pwd=eEt3a2tKMy9sZG5zQXZBRzhFVThzUT09) | Public | For synchronous meetings |
| Forum | [tab Tag](https://forum.getodk.org/tags/tab) | Usually public | Used for public posts with TAB-related content, usually in the [Governance](https://forum.getodk.org/c/governance) category. |
| Forum | [tab Category](https://forum.getodk.org/c/governance/tab) | TAB-only | For private discussions |
| Forum | [@TAB Mention](https://forum.getodk.org/search?q=@TAB) | Public or private, depending on location used | Include in post to request action from TAB. Only TAB can use it, and should be used sparingly. |
| Forum | [Meeting Topic](https://forum.getodk.org/tags/tab-meeting) | Public | Topics created for each meeting. Venue for TAB agenda requests from public. |
| Slack | [#tab](https://getodk.slack.com/channels/tab), [#tab-pulse](https://getodk.slack.com/channels/tab-pulse) | TAB-only | For quick, private ephemeral chat |

## Process

The TAB meets every four weeks for 1 hour. Meetings are open for non-TAB members to listen. See meeting announcements for dates and times.

Meetings are led by a rotating facilitator. The facilitator is responsible for generating an agenda (see below). Anyone can propose agenda items by commenting on the meeting announcement post.

The agenda includes time caps for each item. A time keeper is selected at the beginning of each meeting and is responsible for stopping discussion when time is up.

The TAB uses [consensus-seeking decision-making](https://en.wikipedia.org/wiki/Consensus-seeking_decision-making). When an agenda item has appeared to reach consensus, the facilitator asks for any dissent. If there is dissent, a vote on the issue can be called by any member.

As much as possible, the TAB operates in public.

## Adding new members

To add new members, the Get ODK representative on the TAB will send a forum poll to current TAB members via a shared personal message. The ballot will have a randomized list of candidate names, with links to their application, and a Yes/No option for each candidate. After a predetermined period (typically 72 hours), the votes will be counted and the results will be made public.

## Adding new committers

The [TAB governance](https://github.com/getodk/governance/blob/master/TAB-GOVERNANCE.md) requires that the TAB choose a process for adding new committers. Because discussions about specific community members are sensitive, nominations and voting occurs in a shared personal message with current TAB members on the forum. Selection of a new committer requires consensus approval: three binding +1 votes and no binding -1 votes are required over a 72 hour period. Further, the three binding votes must be from different organizations.

## Roadmap

The purpose of the roadmap is to document and track proposed changes to ODK. The TAB helps Get ODK maintain this roadmap to ensure a coherent and orderly evolution of the tools. Any TAB member can change the roadmap, but changes should typically be made only after consultation with Get ODK and other TAB members.

The roadmap is maintained in [a project in the roadmap repo](https://github.com/getodk/roadmap/projects/1) and has the following categories.

* Proposed: items that are currently being discussed, preferably on a forum topic.
* Under Review: items that have recently been, or currently are, on a TAB agenda for review.
* Approved: items that have been approved by TAB but not yet assigned to a specific owner. Approved items must have an associated issue. Typically these items are planned for release in the next 6 months.
* In Progress: items whose issue has been assigned to an owner and is currently being worked on. Typically these items will be completed in the next 3 months.
* Done: items whose issue have been closed. Typically these items are removed from the roadmap 1 month after completion.

Items on the roadmap should meet one of these requirements:
* Major change to governance, specifications/APIs, or two or more tools.
* Planned breaking change to any tool.
* Deemed noteworthy by a lead developer or TAB members.

TAB members move items through these categories, starting at Proposed and finishing at Done.

Prior to TAB approval, items can be vaguely specified. Discussions to refine these items should take place in a Google Doc, on a user-facing [features category](https://forum.getodk.org/c/features) forum topic, or developer-facing [development category](https://forum.getodk.org/c/features) forum topic or GitHub issue.

If a TAB member deems an item ready for approval, the member can create a [roadmap issue](https://github.com/getodk/roadmap) issue or an issue in the relevant tool's repo. Any item can be discussed by the TAB, but items must have a issue before they can be approved by the TAB. Once approved, the issue becomes the "ground truth" for the item.

## Lazy consensus guidelines

The TAB-GOVERNANCE document specifies: "For internal project decisions, Committers shall operate under Lazy Consensus. The TAB shall establish appropriate guidelines for implementing Lazy Consensus (e.g., expected notification and review time periods)." 

This section lays out those guidelines. Our goal is to allow sufficient time for thoughtful, asynchronous deliberation and feedback by the TAB without unduly impeding the work of those in need of a decision.

If a decision from the TAB is called for in a given matter, a proposal should be made by a committer or TAB member and it should have a deadline included. The TAB must be notified by being @mentioned in a post on the forum. Everyone on the forum can @mention the TAB and the notifications will also appear in #tab-pulse on Slack.

TAB members have at least 72 hours (3 days) to object to proposals. Controversial or breaking changes (e.g., spec additions, feature removal, governance changes) require at least 120 hours (5 days) to object. TAB members can request more time (typically no more than a doubling of the initial time).

TAB members should acknowledge reading the proposal (preferably with a comment) so there is a visible record of their approval. If there are no objections, the proposal can proceed. If there are objections, there should be discussion until there are no more objections or the proposal is withdrawn or rejected.

Asynchronous decisions of the TAB may be made only via the forum, and not GitHub PRs (e.g., for the website) or Slack conversations or emails. This is by design. We want to have a single place (the forum) where all TAB members are expected to respond.

## Meeting Facilitator Checklist

### Pre-preparing

When you are assigned to be facilitator, you may want to set a calendar reminder to do the preparation steps below at least a week before the meeting.

### Preparing

At least one week before the meeting:

1. Construct the agenda.
    1. Open [agenda document](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA/edit).
    1. Create a new page (Cmd+Enter or Insert &gt; Break &gt; Page Break) for the meeting.
    1. Copy the agenda template, found at the very bottom of the document, to that page.
    1. Copy action items from the previous meeting into the new agenda for follow up.
    1. If any items from the previous meeting agenda require more discussion, consider adding them to the current meeting or the parking lot.
    1. Look at the [parking lot](https://docs.google.com/spreadsheets/d/1_vEWH9OFibkC2DuTe7nfy37SgEVLDFI8stGdZKDE5AE/edit#gid=0) for potential agenda items.
    1. For substantive agenda items:
        1. list the goal(s) of the discussion and any things participants should do to prepare for it.
        1. Check in with the presenter to ensure they are ready to present and get a feel for what the discussion will consist of. This ensures you can facilitate it well.
1. Create a thread for the meeting on the [forum](https://forum.getodk.org/).
    1. Title: ODK TAB Call - YYYY-MM-DD
    1. Category: Development
    1. Tags: `tab`, `tab-meeting`
    1. Date/Time: Date and time of the call. Time is always 17:00 UTC.
    1. Content:
        ```
        These calls bring together the Technical Advisory Board for ODK (@TAB) to discuss roadmaps, working groups, and other issues of technical governance. Everyone is welcome to come to these calls, but only TAB members may talk.

        The calls are held every four weeks on [Zoom](https://us06web.zoom.us/j/84959312841?pwd=eEt3a2tKMy9sZG5zQXZBRzhFVThzUT09). We put the agenda and recording of every call [in this document](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA).

        Our next call will be Wed, ENTER_DATE_ONLY_HERE. The meeting time should be shown in your timezone above.

        The agenda is tentatively as follows:

        PASTE_AGENDA_HERE

        The agenda can also be seen in the [agenda document](https://docs.google.com/document/d/1KdUeiryViiPyiG8ajDC_snxSzDBBb-kwNauHvD_chfA/edit#)

        If there are topics you would like to add to the TAB's agenda, please comment below. :point_down:
        ```
1. Monitor the meeting thread for any agenda item requests, adjusting the agenda as needed. If something from the thread doesn’t make it into the meeting, put it in the parking lot.

### Running the Meeting

1. Arrive 5 minutes prior to start time to ensure connected, room setup, etc.
1. Work through the agenda, keeping note of the time.

### Wrapping Up

1. Remind @yanokwa to make the meeting recording public.
1. Add an entry to the [meeting history list](https://docs.google.com/spreadsheets/d/1xD44Km1p0LXoIjBkGxolPvkhq7OXlxA28CN2LKrsT2A/edit#gid=0).
2. Review next meeting time. Ask @yanokwa to update calendar invite time and invitees when necessary.

## Asset Ownership

It is important that key group assets are owned by organizational accounts whenever possible. The group's assets currently include:

* Google Docs/Drive - should be owned by getodk@gmail.com (TAB owns that account)
    * If you create a Google Drive asset that is important for the project and should be long-lived, please transfer ownership to getodk@gmail.com .
* Zoom - administered by yanokwa@getodk.org 
* GitHub projects - administered by yanokwa@getodk.org

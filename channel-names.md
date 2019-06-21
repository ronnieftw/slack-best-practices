Some ideas on how to get started for engineering orgs

_Standardization and consistency is more important than quibbling about any specific naming schema_

### At the org level:

* General public all hands channel, attendance is optional but encouraged. Broader conversation happens here but critical information is shared elsewhere. - e.g. `#platform-org`
* Announcements channel: attendance is expected, important news only. Limit posts here to messages that are must-read.  - e.g. `#platform-announcements`
* A social channel for chatter and banter, attendance is highly optional - e.g. `#platform-random`


### At the team level:

Minimum channel requirements:
* one public channel for general team comms  `#team-foo` – mandatory for all team members
* one public channel for incident triage/on-call `#triage-foo` – mandatory for on-call members, optional for other team members

As the channel volume grows it is recommended to split channel function further:
* one public channel for development conversation `#dev-foo` 
* one public channel for automated alerts `#alerts-foo` 
  
If specific services become large enough to warrant their own support desk:
* a dedicated customer help channel for support requests `#help-foo`

As highest post volume it might be necessary to create:
* a low frequency `#foo-announcements` channel for key updates like service outages or breaking changes that is mandatory for team members and strongly suggested for all cross-functional partners
* a separate `#foo-random` channel to keep social conversation out of the working channels

### At the project level:

Minimum channel requirements:
* `#proj-foo` for general top level conversation including all stakeholders. Milestones, blockers, cadence updates, goes here.

For larger projects:
* `#dev-foo` for engineering discussions including implementation details, bike-shedding and code reviews.
* dev channels can be further broken down by sub-group to ensure conversations are relevant and focused e.g. `#dev-gdpr-foo`

Ephemeral channels:

Ephemeral issues should be temporary channels that are then archived after their need has passed:
* interview candidates: `#intv-ronnie-chen` 
* sensitive or high severity incidents that require a dedicated war-room or a private discussion channel: `#incd-foo-outage`

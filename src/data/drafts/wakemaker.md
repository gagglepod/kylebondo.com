---
title: Wakemaker
publishDate: 19 Aug 2019
description: WordPress Multisite design pattern for clubs.
---

One of the first WordPress Multisite Monster Patterns you may encounter is the Wakemaker. This slow-moving beast resembles a giant sea turtle with a small community on its back, gracefully trolling through the ocean looking for new members to join its journey. If the monster "takes a dive", the community is wiped out with a violent splash, never to be seen again. This means the community needs to make sure the monster is happy and has everything it needs to maintain its steady journey forward. It also means that the tribe living on the back of this beast needs to keep its size in check so as not to over-encumber the Wakemaker, dooming them all to a watery grave.

## Wakemaker Pattern At-A-Glance

The metaphor behind the Wakemaker is ideal for club and association Monster Sites. Each community built on the back of the Wakemaker Monster Site pattern needs to stay in balance with its purpose or be destroyed by the very monster they depend on. This is why the Wakemaker pattern consists of only three distinct sections:

- (A) The main, public-facing "join us" site for attracting new members
- (B) Have 1-3 distinctly branded "event" sites for fundraising events
- (C) A single "members-only" section for providing secure content to members

If done right, the Wakemaker can provide a club or association with a centralized administration, share similar media files, and keep track of each subsite, while managing different themes and audiences. If done wrong, the Wakemaker will become cumbersome to maintain, sink itself in unmanageable content changes, and quickly cause to club or association to lose its prime sources of income: membership dues, event ticket sales, and/or donations.

## Wakemaker Monster Site Pattern

_Fig 1. Wakemaker Monster Site Pattern leverages the centralization power of WordPress Multisite by consolidating a club or association into a network with only three distinct sections: A - Join Us Main Site; B - Event Sub-Site; C - Members-Only Sub-Site_
`mow_diagrams_1c.png`

## Wakemaker Pattern Advantages

### One Ship

Each of the sub-sites within Wakemaker has unique content geared toward different audiences. As a result, the requirements, information layout, and overall designs are all different. However, because there are only a few sites within the network, each site can be asymmetrically connected to the others. For instance, the Join Us site is for those interested in the activities of the club, membership opportunities, and how to contact club leadership for more information. But a key recruiting tool will be a potential member's connection to an event as a volunteer or a participant. Additionally, the Event Site (or one of many event sites) is for those interested in participating in an event, learning about what the event will benefit from, and finding out about registration. So as not to overwhelm or take away from the Event Site\'s purpose, those who come to the event can be sent over to the Join Us site for membership options. Meanwhile, the Members-Only Site is the restricted access area set aside to provide protected content to only those club members that have access. But it can also serve as a tool for reminding members about upcoming events, volunteer opportunities based on scheduled events or identifying new membership requests. Of course, you could create an independent site for each of these sections.

### One Crew

Normally, maintaining 3-5 single-instance WordPress sites would not be too difficult. However, when you consider the first point regarding how all the content is interrelated, combining everything into one Monster Site makes starts to make some sense. But it is in understanding the nature of how clubs and associations staff themselves with regards to managing online content, that is the key to this Monster. Often, clubs and associations are volunteer-based organizations, and because they are volunteer-based, they always seem to suffer from a lack of consistency when it comes to staff. Maintaining 3-5 separate sites as a club is very difficult when the only WordPress-trained volunteers are few and far between. Hiring a freelance developer to manage their sites is not an option for a club running on a shoestring budget, but neither is hiring a full- or part-time staff member. By encapsulating all organizational sites into a Monster Site, the administration manpower needed to keep everything maintained is consolidated into a single, common user interface. They don't need to remember to update each site in their portfolio, they only need to remember to manage one Monster Site. This is extremely important to clubs and associations. Few have time to train someone new on each of the separate ways to log into the WordPress admin, and many forget they even have other sites hanging off their server. By having a consolidated network, clubs and associations can easily remember what sites are within the network, reduce overall training time, and keep their content up-to-date.

### One Port

Another reason for clubs and associations to embrace multisite is to cut back on costs. Most of the member organizations I've encountered are usually non-profit, cash-poor, and always looking for donations. Domain name registration fees and hosting costs are tough to come by, and many rely on members to volunteer (or ask for a very reduced rate) for IT Services to keep the organization online. By making the club or association into a Monster Site, the overall footprint of the site's codebase can be reduced, yet still, allow the organization to leverage the power of multi-purpose sub-domains. Even though the themes are technically different for each subsite, all sites within the monster will have similar media needs (logo, images, color, font) and can benefit from a centralized image repository.

## Wakemaker In Action

The Potomac Velo Club (PVC) is an example of the Wakemaker Monster Site pattern in action. PVC is a cycling club established in 1992 to promote the sport of cycling. Based in Northern Virginia, membership consists of riders at all levels of cycling experience. Some members have been on the racing scene for over 20 years, while others are just starting out.

Their main site is their Join Us section (A) which incorporates a magazine-style blog theme. The club likes to keep its main site populated with recent race reports, club events, and community news content to let potential members know how active the club is within the cycling community. The club currently promotes two big fundraising events a year, Greenbrier Mountain Bike Challenge in the Spring, and Wednesdays at Wakefield Mountain Bike Racing Series in the Summer.

Both event sites use different themes but have similar branding requirements, and connect back to the PVC members-only site for volunteer tracking. Additionally, the PVC members-only site allows members to track the races they race and/or podium in, and the volunteer hours they accrue (both requirements for being members of the club). At one time, these were all separate WordPress sites, each maintained by a handful of PVC members. However, over time, this became difficult to maintain as members moved on or stopped volunteering. By converting this club into a Monster Site, the overall maintenance overhead was reduced and the consolidation made content management easier.

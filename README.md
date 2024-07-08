# Small/Medium-Sized In-Person Data Platform Conference: An Organizer's Checklist

This is a very simple to-do list of to-dos and pitfalls for an organizer of a relatively small Data Platform conference.

The list excludes most of the marketing and sponsor communications, because every event has its own style and persona. But if people don't know about your event, they won't find it.

**Pull requests welcome!**

## Creating a brand-new event

If this is your first time running this event.

- [ ] Create or review your code of conduct, or build on a template, like [SQL Saturday.com's one](https://sqlsaturday.com/coc/).
- [ ] Do you need a domain name? Are you hosting your own event homepage, or does it redirect to SQL Saturday's or Data Saturdays' event page?
- [ ] Create a unique hashtag that you'll use in all communications.

## Planning/preparation

- [ ] Select an event date. Be mindful of public holidays and other events in the region. Collaborate with other regional organizers - with a little planning, you may be able to share speakers.
- [ ] Build your core event team - the people responsible for venue, sponsors, marketing and logistics. You'll have plenty of time to find event volunteers later.
- [ ] Figure out the legal aspects of the event - what legal entity is organizing, what happens to any financial surplus or deficit from the event, etc. A conference will almost certainly run up a $10,000+ budget, so things like taxes will have an impact.

## 6-9 months before the event

- [ ] Create a call for speakers. [Sessionize](https://sessionize.com) is awesome.
  - [ ] Include a time preference field (morning or afternoon).
  - [ ] Include a new-speaker field and/or a mentorship option.
  - [ ] You may want to reinforce that your event is in-person, to avoid any late surprises.
- [ ] Apply for a free community license from Sessionize.
- [ ] Publish your call for speakers, including on [Call for Data Speakers](https://callfordataspeakers.com/event), 
- [ ] Create an event listing on [datasaturdays.org](https://datasaturdays.com/) or [sqlsaturday.com](https://sqlsaturday.com/) if your event comes in one of those two flavors.
- [ ] Start looking for a venue.
  - [ ] Venues are the most expensive part of your event, so don't forget to ask your key sponsor leads about using their premises.
  - [ ] Projectors/screens in all session rooms?
  - [ ] Microphones in large session rooms? Do you need to pay for a technician?
  - [ ] Wifi for speakers and sponsors? Is a password required?
  - [ ] Tables and chairs for sponsors?
  - [ ] Will lights, air conditioning, etc be available and turned on? Important for venues that are not typically used on weekends.
  - [ ] What are the cancellation terms? This is important if you find yourself short of sponsor money, or if you have to cancel the event for some other reason.
- [ ] Build/update a sponsor plan.
  - [ ] Add an estimated number of attendees
  - [ ] Add a rough estimate of the demographics of attendeees (jobs, size of companies, local/national/international, platforms used).
  - [ ] Consider regulating floor space, allowed/disallowed items, alcoholic beverage policy, things like that. Some sponsors may effectively suffocate other sponsors with their huge setups if left unregulated.
  - [ ] Consider creating a formal sponsor contract. Then again, sometimes, getting a sponsor is more important than having them jump through hoops and risk losing them.
- [ ] Consider finding one or more precon speaker(s). [Here's a list](https://callfordataspeakers.com/precon) of people who are interested in doing precons. Well-known precon speakers can drive additional attendees to your event as well as contributing to the overall income for the event.
- [ ] Look into event insurance. The need for insurance will vary considerably between countries and events.

## 3-6 months before the event

### Session selection

- [ ] DM speakers you really want, who may not have seen your call for speakers.
- [ ] Close the call for speakers.
- [ ] Make an initial speaker and session selection. A good mix of well-known and new speakers is best long-term, but a new event might want to prioritize well-known speakers to build an attendee audience.
- [ ] Inform speakers, await confirmation that they will commit to presenting.
- [ ] Announce speakers on social media.

### Venue

- [ ] Finalize the venue terms and contract.
  - [ ] At what time will you get access to the venue?
  - [ ] Is there a loading bay for bulky items?
  - [ ] Is there a kitchen, and/or coffee making facilities?
  - [ ] Who organizes and pays for cleaning?
  - [ ] Will there be parking available for organizers? Sponsors? Attendees?
  - [ ] Are there enough electrical sockets for all sponsors?
  - [ ] Optional: access to rentable displays for sponsors?

### Attendee registration

- [ ] Clean up or reset attendee information from previous years' events.
- [ ] Set up attendee registration platform (for instance Eventbrite, Confetti, etc).
- [ ] Include an option during registration to volunteer at the event.
- [ ] Configure an automation from the registration platform to an email marketing platform (like [Mailchimp](https://mailchimp.com/))
- [ ] For paid lunches, set up a payment workflow (like [Zettle](https://www.zettle.com/), or as part of the registration process). Beware of transaction fees for small transactions.
  - [ ] Consider options for attendees with allergies or other dietary restrictions.
- [ ] Open attendee registration once all the pieces are in place.

## 1-3 months before the event

- [ ] Build the session schedule.
- [ ] Publish the schedule on your event homepage.
- [ ] Open attendee registration.
- [ ] Consider hotel recommendations or deals, but don't take financial risk.
- [ ] Organize travel and/or accommodation for your speakers, if that's something you're offering.
- [ ] Figure out tax/accounting/legal considerations for paid speakers (like precon speakers). Do you need to work out an employment contract or similar?
- [ ] Agreement with catering for lunch, beverages, snacks, coffee.
- [ ] Order badge holders or a badge printing solution.
- [ ] Order lanyards.
- [ ] Order badge ribbons.
- [ ] Order banners/flags/roll-up displays.
- [ ] Email confirmed speakers: How many people are attending the speaker dinner? Bringing a +1? Special dietary requirements?
- [ ] Plan venue and transport for speaker dinner. Remember that the speaker dinner is an important way show your appreciation to speakers for coming to your event. Try to make it special, within the obvious financial constraints of course.
  - [ ] Speakers will often plan to arrive in the evening of the day before, so plan the dinner accordingly. Communicate your plans with speakers.
  - [ ] As with the venue, one of the most expensive items in the budget will be the speaker dinner - understand what your cancellation terms are.
  - [ ] Consider also collecting speakers' phone numbers, in case one of them goes missing.
- [ ] Design and print/order templates for attendee badges.
- [ ] Plan for some nice speaker gifts.

## 2-4 weeks before the event

- [ ] Inform the speaker dinner venue of the final guest count.
- [ ] Select and inform volunteers.
- [ ] Create a volunteer schedule (use a tool like [Doodle](https://doodle.com/en/) to let people pick times that work for them).
- [ ] Set up sponsor lead scanning. I've made a handy
      [leads scanning solution](https://github.com/strdco/scan.datasatsto.se) that uses QR codes on the attendee badge.
- [ ] Speak to sponsors about how scanning/leads registration works. Offer to demo the technical workflow.
- [ ] Set up a session evaluation workflow. I've made a turn-key solution, [eval.datasaturdays.com](https://eval.datasaturdays.com/)
      or [eval.sqlsaturday.com](https://eval.sqlsaturday.com/). All you need is a Sessionize API token.
      But you can also [self-host](https://github.com/strdco/feedback.datasatsto.se), if that's your thing.
- [ ] Email speakers with the sponsor slide and session evaluation URLs.
- [ ] Register speakers and sponsors as attendees, if they haven't already. To make sure they get proper badges, etc.
- [ ] Test to make sure the raffle draw workflow is working the way you want it to.

## Last week before the event

- [ ] Inform catering contractor(s) of the final attendee estimate.
- [ ] Get a name and phone number of an on-site person from the venue. You'll need it.
- [ ] Print time-keeping signs for helpers (10, 5, 1 minute).
- [ ] Print schedules.
- [ ] Purchase any additional powerstrips you may need.
- [ ] Purchase coffee beans, coffee filters, tea bags.
- [ ] Purchase water bottles for speakers.
- [ ] Purchase speaker gifts if you haven't already.
- [ ] Close the attendee registration.
  - [ ] Remove registration link/button from the event homepage.
  - [ ] Print and package all attendee badges.

## Day before the event

Don't plan anything for this day. This is your buffer for unexpected things.

- [ ] Purchase coffee/tea accessories, like milk, honey, sugar. Remember vegan/lactose-free options.
- [ ] Collect any rental equipment like coffee makers, kitchenware, etc.

## Day of the event

This is it. Rise and shine.

### Morning of the event

This is the hands-down most stressful time of the event. The more you can prepare in advance, the more time you have
to fix unexpected emerging issues. Most of these tasks can be done on the day before if you happen to already have access
to the venue.

- [ ] Set up banners, etc at the venue.
- [ ] Prepare registration area.
- [ ] Prepare speaker room. Leave instructions for the Wifi clearly visible to speakers.
- [ ] Inspect AV equipment, make sure mics and projectors/screens are working in all session rooms.
- [ ] Have volunteers standing by to troubleshoot the tech. This is critical for the first round of sessions.
- [ ] Support sponsors in setting up their displays, connecting to the Internet, display screens, etc.
- [ ] Post schedules next to each session room.
- [ ] Post session feedback URLs/QR codes in each session room.
- [ ] Place water bottles/glasses for speakers in each session room.

### During keynote or first session of the event

- [ ] Set up coffee/snack stations, start making coffee.

### End of day

- [ ] Remove schedules, signs.
- [ ] Clean up any left-behind items in session rooms and speaker room.
- [ ] Move back any furniture used in the registration/sponsor area.
- [ ] Clean and pack all the rental equipment.

## After the event

- [ ] Return rental equipment like coffee makers, kitchenware, etc.
- [ ] Email & thank sponsors, include their attendee scans.
- [ ] Email & thank speakers, include session evaluations.
- [ ] Email & thank attendees, include a tentative date for next year's event, links to other events in the region, social links, etc.
- [ ] Submit the event to the MVP portal and report any MVP activities - *only applicable if you're an MVP*.



# Automations

Here are some automations I've built. Unfortunately, most of them are proprietary and not suitable for sharing at this point.

* Webhook: An Eventbrite registration automatically adds the attendee to Mailchimp.
* Powershell: Assign lead scan ID and QR code to attendees.
* Powershell: Synchronize speakers from Sessionize into Mailchimp as attendees.
* Powershell: Extract and process leads scans per sponsor.
* Powershell: Random raffle draw (used at the event).
* Powershell: Clear/reset Mailchimp tags for a new year.
* Node.js: [Generate badges as a PDF document](https://github.com/strdco/badge-printer), including the QR code








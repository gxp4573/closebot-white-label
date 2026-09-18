# white label appointment booking chatbot: how agencies launch a branded AI setter without building one

If you're searching for a white label appointment booking chatbot, you're probably not shopping for a chatbot. You're shopping for a productised service you can put your logo on, charge a monthly retainer for, and not rebuild from scratch every time a new client signs.

That changes what matters. The conversation quality is table stakes. What decides whether the thing is actually sellable under your brand is whether your clients ever see the vendor's name, whether you can re-bill usage at a markup, and whether the setup collapses the moment you hit client number twenty.

This is a look at how that model works in practice, what it costs, and where CloseBot fits — including the parts of its white-label setup that are genuinely useful and the constraints worth knowing before you commit.

## What "white label" actually means in this category

The term gets stretched. In practice there are three separate things vendors call white label, and they're not equal:

1. **Widget branding.** You change the chat bubble colour and add your logo. Cheap, common, and cosmetic.
2. **Portal branding.** Clients log into a dashboard hosted on *your* domain, with your colours, showing their usage and results. This is the part that affects retention.
3. **Build-layer separation.** Only you can edit the agent's logic; the client fills in a handful of variables and uploads knowledge-base content. This is what stops a client from breaking the flow three weeks before renewal.

Most platforms do the first. Fewer do all three, and the third one is where agency operability really lives. A white-label appointment booking chatbot that clients can freely rewrite isn't white label — it's an accident you've handed them.

## The architecture question nobody mentions in the demo

Before comparing tools on features, answer this: where do your leads actually talk to you?

CloseBot is CRM-native, not channel-native. It plugs into HighLevel, HubSpot, LeadConnector, Salesforce, Podio, or a custom CRM, and then handles the text conversations already flowing through that CRM's inbox. It doesn't connect to Instagram or WhatsApp on its own — whatever channel your CRM has wired up is what the agent can answer.

For an agency already running GoHighLevel sub-accounts, that's not a limitation, it's the point. For a solo operator whose entire pipeline lives in Instagram DMs and who doesn't run a CRM at all, it means buying a CRM you didn't want just to reach the agent. Worth being honest about that before you compare monthly prices.

## Where CloseBot fits for agencies that want to resell

CloseBot describes itself as an AI appointment setter: it qualifies inbound leads, handles objections, follows up, and books onto a calendar. The company publishes figures of over 1 million booked appointments, roughly 150,000 messages a day, 99.99% uptime, and 1,000+ agencies on the platform. Those are vendor claims rather than audited numbers, but the volume is at least consistent with a product that's been live for a while rather than a weekend launch.

Its agency angle is concrete:

- A white-label client portal on your domain, with your colours and logo
- Re-billing on messages, seats, storage, and AI token costs, each with your own markup
- Client wallets — clients top up, you pay CloseBot, the difference is your margin
- Variable-driven agents, so one gym-booking agent can serve dozens of gym clients without duplication

That last point is the one that actually scales. In V2 you build a job flow once, define variables like `{amenities}` or `{services}`, and each client fills those in from their own portal. You're not cloning an agent per account, and you're not being asked to maintain twenty parallel flows that drift apart.

👉 [See how the CloseBot agency plan and white-label portal are set up](https://app.closebot.com/a?fpr=li87)

## Every CloseBot plan, and what each one is actually for

The plans page currently shows four tiers. The free tier is genuinely free forever under the message cap, not a 14-day countdown.

| Plan | Best for | What you get | Price | Billing | Get started |
| --- | --- | --- | --- | --- | --- |
| **Free** | Testing the builder or very low lead volume | 1 agent, 1 user seat, 100 messages/month, 1 MB knowledge storage, unlimited account connections | $0 | Always free | [Start on the free plan](https://app.closebot.com/register?fpr=li87) |
| **Core (business)** | Businesses running their own pipeline | Message costs included in the base price, 15+ templates (50+ on annual billing), human support, add-on seats, storage and agents | from **$64/mo** monthly; **$53/mo** equivalent billed annually ($640/yr) | Monthly or annual | [Compare Core business pricing](https://app.closebot.com/settings?tab=subscription&plan=business&toggle=monthly&fpr=li87) |
| **Core (agency)** | Agencies reselling AI setting under their own brand | Unlimited agents, white-label client portal, re-bill all costs, $0.012/message rebillable, 15+ templates | **$397/mo** | Monthly or annual | [Open the agency plan](https://app.closebot.com/settings?tab=subscription&plan=agency&toggle=monthly&fpr=li87) |
| **Growth** | Agencies needing compliance, SLAs, or high volume | HIPAA compliance, quarterly audits, 99.99% priority uptime, priority support, 50+ templates, custom limits | Custom quote | Custom | [Request Growth pricing](https://app.closebot.com/a?fpr=li87) |

A few details that matter more than the headline price:

**Message volume drives the business price.** The Core tier scales with a monthly message allowance — the page shows a slider running from 100 messages up to 100K+, and the price rises with it. Third-party breakdowns of the same tiers list roughly $84 for 1,000 messages, $109 for 2,000, $176 for 5,000 and $454 for 20,000 a month, though those figures aren't printed on the official page, so treat them as indicative rather than quoted.

**Annual billing is roughly two months free.** The $53/mo Core figure against $64 monthly is that same discount applied; it also unlocks the larger template library.

**The Agency plan is flat at $397/month with usage re-billed at $0.012 per message.** Seats beyond the first are $5 each and storage is billed by the megabyte per day, both re-billable. CloseBot tracks AI provider token costs too, and you decide whether to pass those on with markup.

**There's a 7-day trial of any paid plan, and no refunds.** The trial is where you should be doing your testing. Plans run month to month.

## The cost stack agencies forget to price in

A white label appointment booking chatbot isn't a standalone expense if you're running it on top of a CRM. If you're on HighLevel, that's a separate subscription starting around $97/month for Starter. If you're on HubSpot, its paid tiers are their own line item.

So a business wanting around 1,000 AI messages a month is realistically looking at roughly $84 plus a CRM plan — call it $180/month before any channel fees. For an agency, that math reverses: you're charging clients for the booking service, re-billing the message cost with markup, and the platform fee is a cost of goods rather than a subscription.

That's the actual case for the agency tier. It isn't cheaper than the business plan. It's structured so that usage becomes revenue instead of overhead.

## What the white-label workflow looks like end to end

If you've never built one of these, the shape of the work is roughly:

1. **Build the job flow.** Drag-and-drop builder, objective-driven rather than script-based. You're defining what the agent needs to accomplish — qualify, collect fields, book a slot — and the model reasons through the conversation to get there.
2. **Attach a persona.** Personas carry tone, message formatting, response timing, even typo frequency, and they're reusable across agents. Same persona can serve a plumber and a realtor if you're using variables for industry-specific language.
3. **Define client variables.** Business info, services, amenities, service areas — the fields a client fills in themselves from their portal.
4. **Connect the calendar.** A booking node wired to the client's calendar. The agent handles availability, time zones, and confirmation.
5. **Test before going live.** The testing portal lets you run conversations in-flow and roll back changes. You can also pause the agent on any single conversation for a human takeover.
6. **Turn on re-billing.** Wallet-based billing for messages, seats, storage, and tokens, with markup you set.

Steps three through six are where the agency model either holds up or doesn't. Templates help — the paid tiers include 15+ prebuilt flows, with a larger library on annual — but templates get you a starting point, not a differentiated offer.

## Where it works well, and where it doesn't

The conversation quality gets more praise than any feature list. Reviewers on G2 (the product sits around 4.8/5 across roughly 124 reviews) repeatedly mention booking and rescheduling happening naturally in the thread. One thread on r/automation put it bluntly: "way better than GHL chat AI. you can conversationally book appointments and reschedule."

Two operational details stand out from the tooling:

- **Failed bookings get retried** rather than dumping the lead into a "sorry, that slot is taken" dead end. CloseBot claims up to 20% more bookings from this alone — vendor figure, but the mechanism is plausible.
- **Smart FAQ flags questions the agent can't answer confidently** instead of inventing one, then follows up with every lead who asked once you've supplied the answer. A hallucinated discount is the fastest way to lose a client, so this one earns its keep.

The counterweight is that CloseBot is a builder, not a turnkey product. As one G2 reviewer put it: "If the pipeline, messaging, offer, or follow-up logic is sloppy, the AI just scales that sloppiness faster." Nothing here fixes a broken offer.

Also worth flagging before you make it a client-facing promise: CloseBot states support for 40+ languages, but its primary documented language is English, and third-party comparisons note that depth varies by configuration. If you're selling into non-English markets, test that first.

## Quick read on the alternatives

If your clients aren't on GoHighLevel or HubSpot and you want a fully rebranded SaaS product, Stammer.ai is the closest comparison — it's positioned as a white-label AI SaaS platform with flat subscription pricing and full domain and interface customisation. Voiceflow and Kore.ai sit at different price points with different strengths: Voiceflow for bespoke, high-value agents with model flexibility and SOC 2 Type 2, Kore.ai for regulated enterprise clients needing ISO and HIPAA coverage. Tidio's white-label option lives in its partner programme, with Lyro AI and Flows billed separately.

CloseBot's differentiator isn't white-labeling by itself — several tools do that. It's white-labeling *plus* rebilling *plus* deep GoHighLevel integration *plus* appointment-setting-specific tooling like drive-time checks and live property data.

## Common questions

**Do I need a CRM to run a white-label appointment booking chatbot?**
With CloseBot, yes in practice. It connects to HighLevel, HubSpot, LeadConnector, Salesforce, Podio, or a custom CRM, and answers the text channels configured there. There's a standalone mode, but the core value is CRM-native.

**Can I rebill AI costs and keep the margin?**
On the Agency plan, yes — messages at $0.012 each, seats at $5, storage by the MB per day, and AI token costs, all with markup you control. Clients pay into a wallet connected to your Stripe account; you pay CloseBot from yours.

**How much does it cost to start?**
$0. The free plan covers 1 agent and 100 messages a month indefinitely. Paid plans start at $64/month for business and $397/month for agency, both available annual with roughly two months free, and every paid plan has a 7-day trial.

**Can clients edit the agent themselves?**
No, and that's deliberate. Clients fill in predefined variables and upload knowledge-base documents from their portal. The job flow logic stays with you.

**What's the main thing that surprises agencies?**
That message volume is a real budget line. Every tier above the base includes a monthly allowance, and going over pulls from a wallet. If you're quoting clients a flat fee without modelling message volume, you're absorbing the variance.

## The short version

If you're building a productised AI setting offer and your clients already live in a CRM, CloseBot's agency plan is built for exactly that shape of business: your domain on the portal, your markup on usage, one agent serving many accounts. The $397/month only makes sense if you're actually reselling — if you're running it for your own pipeline, Core at $64/month is the plan you want.

If your leads live in Instagram DMs and you have no CRM, this is the wrong category of tool, and adding a CRM to make it work roughly doubles both the bill and the setup.

Start on the free plan, build one agent, and look at whether the conversations your leads actually have get booked. That's a cheaper test than any comparison table.

👉 [Start free and build your first white-label agent](https://app.closebot.com/a?fpr=li87)

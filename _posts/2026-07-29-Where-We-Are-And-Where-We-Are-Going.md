---
layout: post
title: "Where We Are—and Where We Are Going"
date: 2026-07-29
tags: [GreenCloud, business, private cloud, sustainability, computing]
---

Since 2021, GreenCloud has been built around a simple idea: we already own an enormous amount of computing power, so why are we always being encouraged to buy more?

Our laptops, desktops, servers, and GPUs spend much of their lives doing very little. At the same time, organisations continue moving work into public cloud platforms, accepting growing bills and sending increasingly valuable data outside the environments they control.

GreenCloud Business is our answer to that contradiction.

It is a private compute platform designed to help organisations put the hardware they already own to better use. Suitable workloads can run across existing computers, servers, and GPUs while the organisation retains control of its infrastructure and data.

This is not simply a renamed version of the original GreenCloud platform. It is the result of everything we have learned from building GreenCloud, supporting customers, listening to criticism, and being honest about what businesses need before they will adopt something new.

## Times, they are a-changin'

I grew up among the ashes of the engineering majesty of the UK Midlands.

My dad, Robert Leslie Hill—or Burly Bob to his mates—was a true Warwickshire lad who witnessed the rise of the British motor industry. To him, it was almost unimaginable that it could one day disappear; that the people, places, and knowledge behind names such as Rolls-Royce, Rover, and Austin could give way to brownfield land waiting for another purpose.

Everything has its moment.

An idea builds, arrives, and takes centre stage. It can become so dominant that imagining what comes after it feels impossible. Then the world changes, humanity moves on, and something better suited to a new age takes its place.

The same principle is what *drives* GreenCloud. I love a pun.

The first CEO I worked for, Jon Chiplin, used to talk about virtual reality standing at the precipice of adoption, waiting to burst through some metaphorical barrier. I was never quite sure what he meant at the time.

I understand it now. This is how GreenCloud feels to me.

Placing everything in the cloud has become one of the defining assumptions of modern technology. For a time, that assumption made sense. Compute was scarce and expensive. Powerful machines were difficult to own, manage, and connect. Centralising that capability inside large data centres gave organisations access to infrastructure that might otherwise have been beyond their reach.

But times change.

Compute is no longer scarce in the way it once was. It is everywhere. Organisations own fleets of powerful, permanently connected devices, yet most of that capacity remains idle. Networks are faster, hardware is more capable, and software can coordinate work across machines in ways that were impractical when the public-cloud model took hold.

Despite this, the dominant dogma remains: send everything somewhere else.

Public cloud is simply not fit for purpose for a great many jobs. Moving data away from the people and systems that use it can add cost, latency, risk, and dependence on a small number of providers. For many workloads, execution in a distant data centre is no longer a technical necessity. It is an inherited habit.

GreenCloud challenges that habit. It does not isolate compute geographically or restrict it to one rigid mode of operation. It discovers, connects, and uses available computing power wherever it makes sense: on a desktop, a server, a GPU, inside an organisation, or across a wider network of suitable machines.

GreenCloud reflects the world as it is now: connected, distributed, and already rich in computing power.

## Why organisational compute?

A chance conversation with Ewen Anderson of P2Zero, followed by a great deal of research, helped prove the idea: organisational compute is a natural target for GreenCloud.

It gave us a route to address the main criticisms of the original system:

- Speed
- The business model
- Security
- Cost
- Sustainability

During the early development of GreenCloud Business this year, we had a moment that was both funny and revealing.

We were measuring how quickly the platform could execute work on our laptops. Public-cloud services commonly respond in milliseconds—often hundreds of milliseconds once a request has travelled across a network—so we set up our measurements in the same unit.

The result kept coming back as `0`.

We assumed we had found a bug. We had not. We were measuring in the wrong unit.

Our timer reported whole milliseconds, but execution completed before a full millisecond had elapsed and was displayed as `0`. When we changed the measurement from milliseconds to microseconds, we finally got a result.

Keeping compute close to the user and data removed the network journey to a remote data centre. The difference was not merely measurable; it was several orders of magnitude faster than the public-cloud response times we had expected.

It highlighted what has happened almost unnoticed inside modern organisations. As businesses removed their server rooms and moved workloads into the cloud, the computers left behind did not stand still. They were quietly replaced and upgraded. Today's laptops, desktops, servers, and GPUs can be faster, more secure, and more capable than the remote systems many workloads were moved to use—particularly once the cost of sending data back and forth is included.

GreenCloud Business turns that overlooked capacity into an organisational compute platform, bringing work closer to the people, data, and infrastructure that need it.

## Where we are now

GreenCloud Business is under active development, and the important foundations are in place.

We have built the core services needed to register and manage nodes, distribute work, monitor execution, and recover when a machine becomes unavailable. We are also building the dashboard and tools that make the platform useful to people who should not need to understand every detail of the infrastructure beneath it.

The platform can treat an organisation's machines as a controlled pool of compute. A business decides where its work runs, which resources take part, and what happens as those resources change.

We are now moving beyond demonstrations towards recognisable business workloads, including data processing, automation, AI inference, and organisational reporting. Reports are a useful test because tasks must be authorised, dispatched to suitable machines, monitored, and handled safely when circumstances change.

The product is not finished, and we will not hide ordinary development behind an artificial launch announcement. What we have is a working foundation and a route from an ambitious idea to something organisations can trial against real problems.

## Building on what came before

Our first GreenCloud platform, created with the support of Innovate UK funding in 2023, proved that distributed computing across everyday devices can work. It took GreenCloud from an idea to a functioning system and gave us the opportunity to test the principle in the real world.

We should also be honest about it.

Some parts of that platform reflected the available budget, time, and the practical difficulty of implementing something that had not been built before. GreenCloud was not software we could buy off the shelf, rebrand, and take to market. We were creating the technology, operating model, and many of the answers at the same time.

Those decisions were not failures. They were the compromises needed to make a new idea work and discover what the next version should become.

Each iteration has helped us challenge another assumption. GreenCloud Business is becoming faster, more secure, less expensive to operate, and better able to deliver on the environmental purpose that began this journey. We are building on what the original platform proved and carrying its lessons forward.

Technical possibility, however, is only the beginning. Businesses need to understand the financial case, security model, operational impact, and what happens when something goes wrong.

GreenCloud Business is therefore not a universal replacement for public cloud. Public cloud remains a strong choice for workloads requiring rapid, unpredictable scaling or a large global footprint. GreenCloud Business complements it by focusing on work better suited to infrastructure an organisation already owns and controls.

The question is not, "How do we move everything out of the cloud?"

It is, "Which workloads never needed to leave the organisation in the first place?"

## What we want to achieve

Our immediate goal is simple:

By December 2026, we want three paying customers who *get* what we are trying to achieve.

Three organisations with a clear workload, existing infrastructure, and a reason to keep compute close to their own data and policies. Three organisations that see the potential in the computing power they already own and want to help us prove there is a better way to use it.

These early adopters will help us test the technology, installation, support, security, reporting, and commercial model against real needs.

Beyond that, we want to give organisations a practical additional choice. Private-sector companies should be able to reduce unnecessary cloud spend, protect intellectual property, and gain more value from equipment they already own. Public-sector organisations should have a credible route to sovereign computing, keeping sensitive work close to the people, infrastructure, and governance responsible for it.

We also want sustainability discussions to move beyond marketing claims. Reusing available capacity does not make computation free; every workload consumes power. But better use of existing equipment can reduce the pressure to purchase and operate more dedicated infrastructure.

Most importantly, we want to prove that another model is possible.

## See GreenCloud Business for yourself

Writing about distributed compute can explain only so much. Seeing work move across real machines makes the idea much easier to understand.

We are offering a short, live demonstration for organisations interested in reducing cloud costs, private AI, data sovereignty, underused hardware, or having more control over where their computing happens.

We will show you how a device joins the GreenCloud Business network, how a real workload is distributed, and how its progress is followed through the platform. We can then discuss where GreenCloud Business might fit within your infrastructure and which workload could make a useful first trial.

You do not need a finished project or detailed technical plan. Bring us a problem, a workload, or simply your curiosity.

[Book a live GreenCloud Business demonstration](https://www.greencloudcomputing.io/greencloud-business/register-interest).

Alternatively, [email GreenCloud hello@greencloudcomputing.io](mailto:hello@greencloudcomputing.io) and tell us what you would like to run!

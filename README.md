# You don't need AI. You need to you where your data is.

A DevConf talk by Jade Abbott

## Overview

- **The problem:** The real-world failure of AI as a business technology
- **How we got here:** Where the problem stems from
- A detour into democratising business strategy
- **The solution** — you need to know where your data is

## The problem

> Only 10% of companies obtain significant financial benefits from artificial intelligence technologies

~ MIT Sloan Management Review, 2020 study on Expanding AI's Impact with Organisational Learning

AI, ML and data science practitioners experience the frustration of not seeing the fruits of their labours. Their work often doesn't make it into production, and even when it does, it is often unsuccessful as a product.

## How we got here

2011 McKinsey report — Big Data: the next frontier innovation, competition, and productivity

- $300 billion value in US healthcare
- 350 billion Euros in public sector in EU
- $600 billion value of services enabled by processing personal location data

2016 McKinsey report — The Age of Analytics: Competing in a Data Driven World

- Only 50% of value captured in location data
- Only 10% value captured in US healthcare
- Only 10% value captured in EU public sector

2017 Gartner report:

- 60% failure rates for AI projects

Nick Heudecker: 

- Failure rates are actually closer to 85%

2018 McKinsey report — Notes from the AI Frontier

- AI has the potential to deliver additional global economic activity of around $13 **trillion** by 2030

2020 MIT Sloan Management Review:

- Only 10% of companies obtain significant financial benefit from AI technologies

## What is actually happening?

"The Firm" provides *strategy as a service*. Only the "in-club" are qualified to provide this.

Company needs strategy, and pays The Firm to tell them what their 5-year plan is. The Firm says "you need data science and AI". Company sets up a department and hires a team. 5 years later, Company asks The Firm "why are our AI projects failing?" The Firm says "you need to buy more strategy."

What actually happens is that The Firm looks to successful tech companies and assumes that, because they incorporated AI and data science into their strategy, it will work for others as well.

## Democratising strategy

The Toaster Project by Thomas Thwaites

![Toaster](https://pi.tedcdn.com/r/pe.tedcdn.com/images/ted/c0dad5978acf311af98891b7686da155b4faa744_800x600.jpg?c=1050%2C550&w=1050)

Innovation is built on commodoties

Wardley mapping

![Map](https://cdn-cashy-static-assets.lucidchart.com/marketing/blog/2020Q3/wardley-map/Wardley-map-example.png)

Evolution of products:

Genesis -> Custom -> Product -> Commodity

To build innovative products, we need dependent products to be commodified.

## What this means for AI projects

For AI projects, the dependency is on **data**.

The problem is that the data is too undeveloped in terms of evolution.

Examples of problems that AI practitioners deal with:

- Do we have this data?
- Where in the organisation is the data?
- Why is it taking so long to get the data?
- What are these fields?
- Should I even have access to this?
- This data makes no sense
- There are no labels
- The labels are inaccurate
- How do I process this much data?
- What is this data format?
- This data comes from too many sources
- How do I query this?
- Why are data lakes so slow?
- What is a streaming architecture?

The Firm's strategy does not account for this.

## The solution

Using Wardley maps, we can see what The Firm was trying to do...

And we can see what we should actually be focusing on, namely, commodifying data.

What this means in practice:

- Stop hiring data scientists, when we're expecting them to be unicorns who can do SQL, ML, DevOps, software engineering, PowerBI, etc
- Start investing in data governance
- Start hiring data engineers

Data governance is less about rules and regulations, and like having a data librarian. The focus is to enable the organisation to handle things like:

- Data catalogue
- Data privacy
- Data quality
- Data access
- Data lineage

Data engineering ~= ETL; moving data around and transforming it.

Organisations started focusing on developing fancy models too early. They should have been focusing on the data first.

Disband data science departments. Rather build interdisciplinary R&D teams, where data scientists, data engineers, UX people, software engineers etc collaborate. Or even include data scientists on interdisciplinary product teams.

## Links

- This talk at PyConZA: https://www.youtube.com/watch?v=VbxEexY0-0s
- The toaster project: https://www.thomasthwaites.com/the-toaster-project/
- Wardley mapping: https://learnwardleymapping.com/


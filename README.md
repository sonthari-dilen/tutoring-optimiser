# Tutoring Business Optimiser

A data-driven tool to help tutors work smarter — 
fewer hours, better clients, more income.

## The problem

As a private tutor with 15 students and 19 hours of 
teaching per week, I found myself earning less than 
my potential while spending time in the wrong places. 
Evenings were locked up with low-rate sessions, leaving 
no time for career development and networking. 

Meanwhile, without a clear picture of my ideal client, 
I was spending unnecessary time evaluating every new 
student request from scratch.

## What it does

This project analyses a tutoring roster to:

- Identify which students deliver the best return on time
- Flag low-rate sessions that could be referred elsewhere
- Define the ideal client profile by year level, 
  subject, and hourly rate
- Model alternative schedule scenarios 
  (e.g. fewer hours, same or higher income)
- Generate insights for more targeted marketing — 
  knowing exactly who your best clients are means 
  you can advertise to find more of them

## What "done" looks like

- A clear recommendation on which clients to refer 
  to other tutors
- A defined ideal client profile to guide future 
  student intake decisions
- A schedule that protects evenings for 
  networking and career development

## Who it's for

Private tutors who want to move from reactive 
to intentional — optimising their roster for 
income, satisfaction, and sustainability rather 
than just filling hours.

## Tools used

- R / Excel

## Status

Work in progress. Data input and income analysis 
coming first, followed by schedule modelling and 
client profiling.

## What I'm learning

How to apply data analysis to a real business problem 
I actually own. This project is part of my transition 
into biostatistics — practising structured 
problem-solving with messy, real-world data.

## Methodology

This project follows a three-step process:

**Step 1 — Variable identification**
Brainstorm and define the variables that 
characterise an ideal tutoring client 
(e.g. effective hourly rate, attendance, 
energy cost, longevity).

**Step 2 — Client rating**
Score each current client against every 
variable on a 1–5 scale. Some variables 
are backed by hard data (hourly rate, 
attendance records); others are scored 
on informed judgement (rapport, parent 
communication style).

**Step 3 — Weighted scoring model**
Apply weights to each variable based on 
personal priorities, then calculate a 
composite ideal-client score per student. 
Built first in Excel, then rebuilt in R 
to enable sensitivity analysis and 
richer visualisation.

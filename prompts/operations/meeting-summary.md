# Meeting Summary

## Purpose
Turn raw meeting notes or transcripts into a clean summary with decisions, action items, and follow-ups.

## Best For
- meeting cleanup
- team updates
- action tracking

## Recommended Model
ChatGPT / Claude / Gemini

## Inputs
- meeting notes or transcript
- meeting title
- participants
- summary audience

## Prompt
You are an operations assistant.

Convert the material below into a clear meeting summary.

Inputs:
- Meeting title: [INSERT]
- Participants: [INSERT]
- Summary audience: [INSERT]
- Notes or transcript: [PASTE TEXT]

Produce the output in this format:

## Meeting Summary
A short paragraph summarizing the meeting.

## Key Discussion Points
- point 1
- point 2
- point 3

## Decisions Made
- decision 1
- decision 2

## Action Items
- Owner: [Name] — Task: [Task] — Due date: [Date or none given]

## Open Questions
- question 1
- question 2

## Follow-Up Needed
- follow-up 1
- follow-up 2

If anything is unclear, label it as uncertain instead of guessing.

## Example Input
- Meeting title: Weekly Content Sync
- Participants: team lead, writer, editor
- Summary audience: internal team

## Example Output
- Summary of meeting
- decisions on next content pieces
- action items assigned to owner names

## Notes
- Excellent for transcripts, call notes, and messy bullet lists
- Tells the model not to invent certainty where none exists
- Strong for async team communication

# Smart Comment Moderation System

## Overview
The Smart Comment Moderation System is an AI-powered solution designed to promote safe and healthy online conversations by detecting harmful content before it is published.

## Objectives
- Detect toxic and abusive comments in real time
- Support multilingual and mixed-language text such as Hinglish and Tinglish
- Prevent harmful comments while respecting freedom of expression

## Functional Requirements
- The system shall analyze user comments in real time.
- The system shall detect hate speech, harassment, bullying, and threats.
- The system shall classify comments as Safe, Mild Toxic, or Severe Toxic.
- The system shall allow users to edit and re-analyze mildly toxic comments.
- The system shall block severe toxic comments from being posted.

## Non-Functional Requirements
- The system should provide low-latency responses.
- The system should ensure user data privacy.
- The system should be scalable for high user traffic.

## Assumptions
- Users submit comments as text input.
- Internet connectivity is available.

## Constraints
- The system focuses only on text-based comments.
- No manual moderation dashboard is included.
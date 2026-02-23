# Architecture

## Purpose

agent-infra-auto-stream-resolver-web-jdt evaluates service health and change events to reduce operational risk.

## Components

- Signal intake layer
- Assessment engine
- Output formatter for downstream automation

## Runtime Flow

1. Receive signal text/event.
2. Compute deterministic risk score.
3. Emit structured assessment result.

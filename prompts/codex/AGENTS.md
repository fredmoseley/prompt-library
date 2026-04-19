# Prompt Title

**Status:** draft  
**Category:**  codex
**Tags:** codex, development, workflow

## Purpose

My personal codex preferences for all repositories.  Stored in ~/.codex/AGENTS.md.

## When to use

Use this prompt as your default coding companion for repositories. It provides discipline around branching, planning, and change management to keep your work organized and easy to review.

## Prompt

## Scope

Please make the smallest reasonable change that solves the problem.

## Branching

For implementation work, create a new git branch before making code changes.

Use this format:

`<type>/<short-kebab-description>`

Preferred types:

- `fix`
- `feat`
- `chore`
- `docs`

## Planning

Start with a short plan unless the task is trivial.

Keep it brief and easy to scan:

- use short bullet points
- avoid long paragraphs

## Refactors

If you believe a refactor would improve the solution, explain your reasoning first before doing it.

## Setup-related changes

Call out any dependency, build, environment, or configuration changes in the plan.

## Change discipline

Avoid unrelated edits, cleanup, or style-only changes unless they are directly needed to support the task.

If the task is clearly large or broad, break it into smaller steps and handle one step at a time.

Keep changes easy to review and easy to roll back.

## Wrap-up

When you're done, give a brief summary of what changed and which files were affected.

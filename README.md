# Japanese Sentence Miner

Automated N+1 sentence mining tool with Anki integration for Japanese language learners.

## Overview

A web application that automatically syncs with Anki, analyzes Japanese text, and extracts sentences with exactly one unknown word (N+1 learning) to create optimal flashcards.

**Key Features:**
- Automatic bidirectional sync with Anki via AnkiConnect
- Japanese text difficulty analysis (JLPT N5-N1)
- N+1 sentence extraction (sentences with exactly 1 unknown word)
- Auto-add mined cards directly to Anki deck
- Known vocabulary tracking

## Problem Statement

Manual sentence mining is time-consuming. Anki cannot filter for sentences with exactly one unknown word, which is optimal for vocabulary acquisition.

## Solution

Automatically sync vocabulary from Anki, paste any Japanese text, and get perfectly-filtered N+1 sentences added back to Anki instantly.

## Tech Stack

- **Backend:** Go, Chi Router, Kagome (Japanese NLP)
- **Database:** PostgreSQL, Redis
- **Infrastructure:** Docker
- **Integration:** AnkiConnect API
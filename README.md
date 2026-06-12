# Text Model as One Feature

A project page about using an NLP sub-model as a single meta-feature instead of feeding sparse text directly into the main model.

## Project Website

[View Project Site](https://mah-trigui.github.io/text-model-as-one-feature/)

## Overview

This project used partially decoded support-case text as a separate NLP modeling stream.

Instead of mixing thousands of sparse TF-IDF columns directly into the main structured model, the text model was first trained independently and its score was injected as one feature.

## Core Idea

The NLP sub-model’s output probability became a compact structured signal:
- text first
- summary score second
- final model last

## Architecture

![Architecture](images/architecture.jpg)

## Key Takeaway

**I turned the text model into one feature.**

## Public Scope

This repository shares the feature-level stacking idea, selected implementation logic, and project presentation only.

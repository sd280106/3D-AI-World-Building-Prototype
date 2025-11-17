# 1. Overview
This project aims to build a prototype system capable of generating 3D scenes using AI-driven world-building logic, based on user inputs such as genre, story context, and environment descriptions.
The system focuses on enabling early-stage pre-production workflows for filmmakers, game developers, and writers by rapidly generating initial world concepts.

This document defines the Minimum Viable Product (MVP) for the prototype.

# 2. MVP Description
The MVP is a minimal, working version of the model that takes a short text prompt describing a scene (e.g., “A dark fantasy forest with a ruined castle”) and outputs:

- Parsed semantic information (genre, objects, mood).

- A simple object layout represented in a structured JSON file.

- A lightweight 3D mock scene, rendered as a placeholder image (basic shapes / placeholder models arranged in 3D space).

- A fully logged output documenting how the AI interpreted the user’s input.

This MVP does not require high-quality 3D generation, physics, or photorealistic rendering.
It only needs to prove the end-to-end pipeline works, establishing the foundation for full world-building in later phases.

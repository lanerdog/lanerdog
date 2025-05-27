# AI Uncensored Story Generator

This repository contains the front-end HTML for an AI Uncensored Story Generator.

## Description

The `index.html` file provides the user interface for generating stories paragraph-by-paragraph based on user overview and instructions. It includes features for:
- Story overview input
- Displaying the story so far
- Input for what should happen next
- Buttons for regenerating, deleting, and rating paragraphs
- LocalStorage integration to remember story progress and settings
- Dark mode and other UI enhancements

## How to Use

1.  Clone this repository or download the `index.html` file.
2.  Open `index.html` in a modern web browser.

## Important Dependencies and Missing Functionality

The `index.html` file, as provided, relies on several external JavaScript functions and plugins that are **not** included directly in the code. These are essential for the full functionality of the story generator, particularly the AI-powered text generation.

**Missing Functions and Placeholders:**

The following JavaScript functions are called within `index.html` but are not defined:
- `updateLastParagraphButtonsDisplayIfNeeded()`
- `updateButtonsDisplay()`
- `rateLastMessage(type)`
- `continueStory(options)` (Core function for story generation)
- `deleteLastParagraph()`
- `undoDeleteLastParagraph()`
- `generateWhatHappensNextIdeas()`
- `generateWhatHappensNextIdeas2()`
- `generateWhatHappensNextIdeas3()`
- `generateWhatHappensNextIdeas4()`
- `generateWhatHappensNextIdeas5()`
- `copyStoryTextToClipboardWithoutSummaries()`
- `tabbedCommentsPlugin(options)` (and its dependencies `commentChannels`, `defaultCommentOptions`)
- `commentsPlugin(options)`
- `createCommentsSectionHtml()`

Additionally, there is a placeholder `[fullscreenButton(...)]` in the HTML that needs to be implemented or replaced with a working JavaScript function.

**Likely Sources:**

Comments within `index.html` suggest that these functionalities are intended to be provided by plugins from `perchance.org`, specifically:
- `perchance.org/ai-text-plugin`
- `perchance.org/remember-plugin` (or similar, for localStorage interactions)
- Plugins for comments and UI elements.

**To achieve full functionality:** These external scripts and their dependencies would need to be correctly sourced and integrated into the page. This task is beyond the scope of simply creating the `index.html` file based on the provided issue. The current `index.html` provides the structure and client-side interactions, but the core AI generation and advanced features will not work without these external components.

## Features (Intended, from Issue Description)
The original issue mentioned that this version aims for:
- Improved variety of generated names
- Increased unpredictability
- Improved character development
- Added some priority to unique speaking styles

These features are dependent on the AI backend and the successful integration of the aforementioned plugins.

# project # Slide 1 — Title Slide

## PROG6221 — Programming 2A

### Part 2: GUI Cybersecurity Awareness Chatbot

**Presented by:** Your Name
**Student Number:** Your Student Number
**Year:** 2026

---

# Slide 2 — Project Overview

## What I Built

* Converted the Part 1 console chatbot into a GUI application using WPF/WinForms
* Added cybersecurity keyword recognition
* Implemented randomised responses
* Added sentiment detection and conversation memory
* Included voice greeting and ASCII art branding

### Goal

To create an interactive chatbot that educates users about cybersecurity awareness.

---

# Slide 3 — GUI Design

## Interface Features

* Chat display area for conversation history
* User text input field
* Send button for interaction
* Clean colour scheme and organised layout
* ASCII art/logo displayed on startup
* Voice greeting when the application launches

### Design Focus

* Easy to use
* Visually appealing
* Professional appearance

---

# Slide 4 — Keyword Recognition

## Cybersecurity Topic Detection

The chatbot detects keywords such as:

* Password
* Phishing
* Scam
* Malware
* Privacy

### Example

User Input:

> “Tell me about passwords”

Bot Response:

> “Use strong passwords with uppercase, lowercase, numbers, and symbols.”

### Implementation

* Used `string.Contains()`
* Responses stored inside dictionaries

---

# Slide 5 — Random Responses

## Making the Bot Feel Natural

* Multiple responses stored for the same topic
* Random selection used during conversation
* Prevents repetitive answers

### Technologies Used

* `List<string>`
* `Random` class

### Example

Every time the user asks about phishing, the chatbot may provide a different tip.

---

# Slide 6 — Conversation Flow

## Maintaining Context

The chatbot remembers the current discussion topic.

### Features

* User can say:

  * “Tell me more”
  * “Explain further”
  * “Another tip”

* Bot continues discussing the same topic

### Implementation

* `currentTopic` variable stores the active discussion

---

# Slide 7 — Memory and Recall

## Personalised Interaction

The chatbot stores user information such as:

* User name
* Favourite cybersecurity topic

### Example

> “Since you are interested in privacy, here is another safety tip.”

### Data Structure Used

* `Dictionary<string, string>`

### Benefit

Creates a more engaging and personalised experience.

---

# Slide 8 — Sentiment Detection

## Understanding User Emotions

The chatbot recognises emotional words like:

* Worried
* Confused
* Frustrated
* Curious
* Scared

### Behaviour

* Gives reassuring responses when users seem worried
* Gives enthusiastic responses when users are curious

### Example

User:

> “I am worried about scams.”

Bot:

> “It’s good to stay alert. Never click suspicious links from unknown sources.”

---

# Slide 9 — Code Structure

## Object-Oriented Programming

### Classes Used

* `ChatBot`
* `ResponseManager`
* `SentimentAnalyser`
* `MemoryStore`

### Features

* Clear separation of responsibilities
* Reusable methods
* Easy maintenance and expansion
* XML comments added to public methods

### Benefit

Improves code organisation and readability.

---

# Slide 10 — Demonstration and GitHub

## Live Demonstration

During the demo:

* Show the GUI interface
* Demonstrate keyword recognition
* Show random responses
* Demonstrate memory recall
* Show sentiment detection

## GitHub Requirements

* Minimum 6 commits
* 2 releases/tags
* Continuous Integration working successfully

### Conclusion

The chatbot successfully combines GUI development, cybersecurity awareness, and intelligent conversation features into one application.

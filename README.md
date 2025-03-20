### Lunette - Project Overview

**Lunette** is a charming, custom helper robot designed to be your delightful conversational companion. Built on a modified vacuum cleaner chassis for graceful mobility, Lunette glides around your space and chats with you using AI-powered dialogue. Programmable with Arduino (directly into the vacuum cleaner’s firmware) and networked for API integration, this robot blends elegant movement with a sweet personality.

#### Overview

Lunette aims to:
- Roam effortlessly using a vacuum cleaner base.
- Engage in playful, real-time conversation through onboard audio and AI.
- Reflect a feminine, whimsical charm tailored to your style.
- Offer a customizable platform for robotics enthusiasts.

#### Features
- **Mobility**: Vacuum cleaner chassis for smooth, flowing navigation.
- **Conversation**: Microphone and speaker for lively, two-way chats.
- **AI Integration**: API-driven responses for natural, girly banter.
- **Modular Design**: Flexible hardware and software for personalization.

#### Hardware Requirements
- Vacuum cleaner (preferably with accessible firmware or motor control).
- Arduino microcontroller (e.g., Arduino Uno or Mega).
- Microphone and speaker module (e.g., USB audio or I2S-based components).
- Sensors (ultrasonic, IR) for obstacle avoidance.
- Wi-Fi module (e.g., ESP8266) for network connectivity.
- Power supply (battery or vacuum cleaner’s existing power system).

#### Software Requirements
- Arduino IDE or vacuum cleaner firmware tools.
- API client library (e.g., for AI services like OpenAI or Google Cloud Speech-to-Text).
- Python or C++ for AI integration and control logic.
- Speech recognition and synthesis libraries (e.g., Google TTS/STT).

#### Getting Started
1. Assemble the hardware: Mount the microphone, speaker, and sensors on the vacuum chassis.
2. Program the Arduino or flash the vacuum cleaner firmware with basic movement and audio code.
3. Set up the AI API credentials for conversational magic.
4. Launch Lunettea and start chatting as she roams!

#### Next Steps
See the roadmap below for a detailed development plan.

#### Contact
Questions? Reach out to me directly—I’d love to help Lunette come to life!

---

### Roadmap to Complete Lunette

Here’s the updated roadmap:

#### Phase 1: Concept and Design
- **Goal**: Shape Lunette’s structure and chatty personality.
- [ ] Research vacuum cleaner models with hackable firmware (e.g., Roomba) or plan Arduino motor control.
- [ ] Sketch her design: vacuum base, microphone/speaker spots, sensor placement, and power layout.
- [ ] Pick audio components (e.g., a small USB microphone and speaker with a soft tone).
- [ ] Design a 3D model of her chassis and mounts in CAD (e.g., Fusion 360), maybe with a small accessory.

#### Phase 2: Hardware Assembly
- **Goal**: Build Lunette’s physical form.
- [ ] Disassemble the vacuum cleaner to access motors and power supply.
- [ ] Integrate Arduino with motor drivers (e.g., L298N) if firmware isn’t hackable.
- [ ] Mount the microphone and speaker on chassis.
- [ ] Add sensors (ultrasonic for distance, IR for edges) and wire them to Arduino.
- [ ] Install a Wi-Fi module (e.g., ESP8266) for network access.
- [ ] Test power to keep moving and talking gracefully.

#### Phase 3: Basic Software Development
- **Goal**: Get Lunette rolling and chatting.
- [ ] Write Arduino code for motor control (forward, backward, twirl).
- [ ] Set up audio: record or generate voices, play her sweet responses.
- [ ] Test sensors for obstacle avoidance and add simple navigation.
- [ ] Debug firmware so her mobility and voice work in harmony.

#### Phase 4: AI and Network Integration
- **Goal**: Give Lunette witty, girly voice.
- [ ] Pick an AI API (e.g., OpenAI for fun dialogue, Google Cloud for voice processing).
- [ ] Write a Python script to:
  - Capture audio and words, send them to the API, and get replies.
  - Turn text into a soft, playful voice for her speaker.
- [ ] Add AI navigation (e.g., glide toward you when called).
- [ ] Test network and response speed while she moves.

#### Phase 5: Testing and Optimization
- **Goal**: Tune Lunette’s charm and performance.
- [ ] Test her fully: roam, chat (e.g., “Lunette, tell me something sweet!”).
- [ ] Tweak audio for clarity and tones.
- [ ] Refine AI for fun, context-aware replies.
- [ ] Add fail-safes (e.g., pause and giggle if stuck).

#### Phase 6: Final Touches
- **Goal**: Customise Lunette for people or places.
- [ ] Document setup with notes, photos, or videos.
- [ ] Add personal touches (e.g., a bow or LED lights for flair).

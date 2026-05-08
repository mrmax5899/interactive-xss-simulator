# Extreme XSS Visualizer

An advanced, interactive single-page application (SPA) built to demonstrate the mechanics of Reflected Cross-Site Scripting (XSS). This educational tool visualizes the entire attack flow—from the victim's browser, across the network, into the vulnerable backend server, and back to the client's DOM.

### ✨ Key Features:
- **Interactive Animations:** Watch the HTTP packets travel between the Client and Server in real-time.
- **Dynamic Payload Execution:** Inject custom payloads (e.g., `<script>alert('HACKED')</script>`) and see them dynamically reflect and execute in a safe, simulated browser environment.
- **Network Inspector:** View complete, realistic HTTP Request and Response headers and body content.
- **Instructor Controls:** Built-in Pause/Play functionality (Spacebar shortcut) allows instructors to freeze the animation at any state to explain complex concepts to students.
- **Vulnerable Code Highlighting:** Visually highlights the exact line of vulnerable backend PHP code where the sanitization failure occurs.

Ideal for cybersecurity bootcamps, university lectures, and ethical hacking demonstrations.
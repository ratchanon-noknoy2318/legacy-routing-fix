# Kosamphi ITA 2024

Production Legacy System for Integrity and Transparency Assessment (ITA)

---

## Overview

This repository represents a production-grade legacy PHP system used by the Kosamphi Nakhon District Health Office under the Ministry of Public Health (MOPH) network.

The system is responsible for managing Integrity and Transparency Assessment (ITA) workflows, including data collection, evaluation, and reporting processes in a real-world government healthcare environment.

This project reflects hands-on experience working with and maintaining a legacy codebase in production.

---

## Impact

* Actively used in a government healthcare organization
* Supports real ITA evaluation and reporting workflows
* Handles structured administrative and compliance data
* Improves transparency and operational efficiency
* Integrated into MOPH production infrastructure

---

## System Context

Traditional ITA processes relied on fragmented and manual workflows across multiple systems.
This platform centralizes data management and standardizes evaluation processes within a single web-based system.

---

## Engineering Responsibilities

* Maintained and modified a legacy PHP codebase in production
* Implemented updates based on evolving ITA requirements
* Ensured system stability during changes and deployments
* Debugged and resolved issues in a live environment
* Improved code readability and organization where applicable

---

## Legacy System Experience

* Worked with non-modular, tightly coupled PHP architecture
* Navigated limited or undocumented codebase
* Applied changes without disrupting existing workflows
* Balanced short-term fixes with long-term maintainability
* Adapted to constraints of existing infrastructure (MOPH network)

---

## Challenges

* Maintaining system stability in a production environment
* Understanding and modifying legacy code without documentation
* Handling inconsistent data structures
* Ensuring compatibility with existing workflows and users
* Working within infrastructure constraints

---

## Architecture Overview

```
[User / Staff]
      ↓
[PHP Application (Monolithic)]
      ↓
[MySQL Database]
      ↓
[MOPH Network Infrastructure]
```

---

## Tech Stack

| Layer      | Technology             |
| ---------- | ---------------------- |
| Backend    | PHP (Legacy)           |
| Database   | MySQL                  |
| Frontend   | HTML, CSS, JavaScript  |
| Deployment | MOPH Government Server |

---

## Project Structure

| Path         | Description             |
| ------------ | ----------------------- |
| `/pages`     | Core application pages  |
| `/component` | Reusable UI components  |
| `/main-menu` | Navigation logic        |
| `/ita-data`  | ITA dataset and records |
| `/variable`  | Global configuration    |
| `/tb`        | Table processing logic  |
| `/css`       | Stylesheets             |
| `/css-js`    | Client-side scripts     |
| `/img`       | Static assets           |
| `/index.php` | Entry point             |

---

## Deployment

The system is deployed and actively used in a real-world environment:

* Organization: Kosamphi Nakhon District Health Office
* Infrastructure: MOPH Production Network
* Access: https://kosamphi.moph.go.th/ita/ita2024

---

## Future Improvements

* Refactor legacy PHP structure into modular architecture
* Introduce API layer for better separation of concerns
* Migrate to modern frameworks (e.g., Next.js, Node.js)
* Improve maintainability and testability
* Enhance UI/UX for better usability

---

## Author

**Ratchanon Noknoy**
Software Engineer

---

## License

MIT License © 2024 Ratchanon Noknoy  
*This project was developed as an internship project in 2024.*

# STUDYSTART

**My pair partner:** Iqbal Tawakkal Sobari  
**Tool we had to use:** Bolt.new  
**SDG we had to address:** SDG 4 - Quality Education

## What problem does it solve, and for whom?

Our project is aimed at **new international students at The Hague University of Applied Sciences (THUAS)** who need extra support understanding how studying at THUAS works.

For new international students, systems such as Brightspace, OSIRIS and MyTimeTable can be unfamiliar. The Dutch higher-education system may also work differently from what they are used to. Some students may hesitate to ask for help when they are confused, which can make relatively simple problems harder to solve.

Our goal is to make this information easier to understand so students can become more independent and confident during their studies.

## What did you build?

We built an interactive onboarding and learning web app with five modules:

- Brightspace
- MyTimeTable
- Studying in the Netherlands
- Getting Help
- OSIRIS

Students can go through short explanations and realistic examples, answer knowledge-check questions and receive feedback. The app also keeps track of completed modules and quiz scores in the browser and provides links to relevant THUAS systems and support information.

## Link to the live thing

**Live website:** https://thuas-international-p9es.bolt.host/

## How do I run it?

Visit the link: https://thuas-international-p9es.bolt.host/

## Who did what?

### Haki Abdulovski

* Prompt engineering, working on bolt.new

### Iqbal Tawakkal Sobari

* Making the video, ethical reflection

**Shared work:**

* Making the presentation

## Ethical reflection

1. Exclusions and Implicit Assumptions
When designing a digital support platform for vulnerable international students, it is critical to recognize who the system serves and who it inadvertently leaves behind:

Assumptions About the Learner:

Technology & Connectivity: The system assumes that every student owns a modern personal device (smartphone or laptop) and has continuous access to a stable internet connection.

Language Proficiency: The platform assumes a functional proficiency in English.

Digital Literacy: It assumes the student possesses basic digital skills, such as navigating web dashboards, interpreting prompt-based systems, and managing university login credentials.

Excluded Groups:

Students in Digital Poverty: Students who cannot afford personal laptops, modern smartphones, or reliable data plans.

Students with Severe Language Barriers: Non-English background students who struggle with academic English or administrative terminology in their first few months.

Students with Disabilities: Neurodivergent students or visual/hearing-impaired users if the tool does not strictly adhere to WCAG (Web Content Accessibility Guidelines) standards.

2. Potential Misuse and Negative Effects
Technology built with good intentions can still be leveraged for the "wrong reasons" or lead to unintended harm:

Over-Reliance & Loss of Independence:

Misuse: Students may rely entirely on the AI platform to solve every academic or administrative challenge instead of learning to navigate real-world Dutch systems independently.

Effect: This creates a passive dependency, reducing critical thinking and delaying social integration into the physical university community.

Privacy Exploitation & Data Sharing:

Misuse: Students asking financial or personal questions (e.g., regarding DUO, student loans, or visa status) might input sensitive personal details (BSN numbers, passport copies, financial bank statements) directly into the system.

Effect: Improper handling or logging of this sensitive data could lead to severe privacy breaches or identity theft risks for vulnerable individuals.

Misuse of the Peer / Buddy Matching System:

Misuse: Unverified users or bad actors could exploit the study-buddy feature for spamming, harassment, or commercial exploitation.

Effect: This compromises student safety and undermines the psychological trust required for a safe learning environment.

3. Mitigation Strategies & Ethical Safeguards
To minimize these risks and ensure equitable access, the following safeguards are built into the design:

Human-in-the-Loop Oversight: The AI acts strictly as an initial navigational guide. For complex, high-risk, or personal matters (such as financial hardship or mental health), the system immediately routes students to human THUAS advisors and counselors.

Data Privacy Boundaries: The platform enforces strict data minimization. Prompts explicitly warn users never to share personal identifiers (like BSN numbers or passwords), and no private user logs are sold or stored for training external models.

Multi-Channel & Accessible Fallbacks: To prevent digital exclusion, essential guides and resources remain available via offline-accessible PDFs and physical student service desks across THUAS campuses.

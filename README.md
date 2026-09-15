<div align="center" style="border: 2px solid #ccc; padding: 20px; border-radius: 12px; width: 80%; margin: auto; box-shadow: 0 0 10px rgba(0,0,0,0.15);">
    <img
        width="180"
        height="220"
        alt="Logo - SURE ProEd"
        src="https://github.com/user-attachments/assets/88fa5098-24b1-4ece-87df-95eb920ea721"
        style="border-radius: 10px;"
    />

  <h1 align="center" style="font-family: Arial; font-weight: 600; margin-top: 15px;">SURE ProEd (formerly SURE Trust) 
      </h1>
<h2 style="color: #2b6cb0; font-family: Arial;">Skill Upgradation for Rural youth Empowerment Trust</h2>
</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

<div style="padding: 20px; border: 2px solid #ddd; border-radius: 12px; width: 90%; margin: auto; background: #fafafa; font-family: Arial;">

<h2 style = "color:#333;"> Student Details </h2>
<div align = "left" style ="margin: 20px; font-size: 16px;">
    <p><strong>Name:</strong> Jay Beedkar </p>
    <p><strong>Email ID:</strong> jaybeedkarg4genai@gmail.com </p>
    <p><strong>College Name:</strong> SURE Trust Skill Development Network </p>
    <p><strong>Branch/Specialization :</strong> Generative AI </p>
    <p><strong>College ID:</strong> Jay Beedkar-G4 GenAI </p>
</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

<h2 style="color:#333;"> Course Details </h2>
<div align="left" style="margin: 20px; font-size: 16px;">
    <p><strong>Course Opted:</strong> G4 GenAI </p>
    <p><strong>Instructor Name:</strong> Sir Prujith Radhakrishnan </p>
</div>
<div align="left" style="margin: 20px; font-size: 16px;">
    <p><strong>Duration:</strong> 60 Days (May 2026 - July 2026) </p>
</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

<h2 style="color:#333;"> Trainer Details </h2>
<div align="left" style="margin: 20px; font-size: 16px;">

<p><strong>Trainer Name:</strong> Sir Prujith Radhakrishnan</p>
<p><strong>Trainer Email ID:</strong> </p>
<p><strong>Trainer Designation:</strong> Course Mentor</p>
</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

## **Table of Contents**
- [Course Learning](#course-learning-to-be-edited-by-student)
- [Projects Completed](#projects-completed)
- [Project Introduction](#project-introduction)
- [Technologies Used](#technologies-used)
- [Roles and Responsibilities](#roles-and-responsibilities)
- [Project Report](#project-report)
- [Learnings from LST & SST](#learnings-from-lst--sst)
- [Community Services](#community-services)
- [Certificate](#certificate)
- [Acknowledgments](#acknowledgments)

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />


## Overall Learning 

During this course (G4 GenAI), I learned the principles of Generative AI engineering, stateful multi-agent workflows, computer vision perception, and graph database storage. I gained hands-on experience building cooperative AI agent chains with LangGraph, running YOLOv8 object tracking models frame-by-frame on raw video footage, and mapping entity-relation crime topologies using SQLite, NetworkX, and Neo4j. This training has equipped me to design and develop enterprise-level agentic applications.


<h2 style="color:#333;"> Projects Completed </h2>
<div align="left" style="margin: 20px; font-size: 16px;">

<p><strong><a href="#project1">Project 1:</a></strong> Sentinel AI - Multi-Agent Crime Investigation System</p>


<p><em>(You can add more projects as needed)</em></p>

</div>

<!-- Project 1 -->
<h3 id="project1">Project 1: Sentinel AI - Multi-Agent Crime Investigation System</h3>
<p>
  Sentinel AI is a state-of-the-art, autonomous, multi-modal cognitive crime investigation system designed to empower forensic investigators, police departments, and security analysts. Modern criminal investigations are heavily constrained by data silos, cognitive fatigue, and manual correlation delays. Investigators routinely spend dozens of hours manually cross-referencing hundreds of gigabytes of raw CCTV feeds, audio transcripts, conflicting witness testimonies, and suspect records. This manual bottleneck significantly delays critical breakthroughs, leads to evidence oversight, and introduces subjective human error. Sentinel AI addresses these systemic challenges by bridging real-time computer vision using Ultralytics YOLOv8 with a cooperative network of specialized LLM reasoning agents orchestrated through LangGraph. The system ingests multi-modal case evidence, ranging from CCTV video files (.mp4) and audio testimonies to raw witness text statements. The computer vision engine samples video footage at 1 Frame Per Second (FPS), identifies physical entities such as suspects, vehicles, bicycles, weapons, and backpacks, and records timestamped physical evidence points. Concurrently, specialized sub-agents, including the Evidence Analyzer, Timeline Builder, Contradiction Detector, and Suspect Reasoner, execute parallel evaluations to reconstruct verified timelines, flag statement inconsistencies, and rank suspects based on Motive, Means, and Opportunity. The complete investigative workflow is packaged inside an in-process, single-port Streamlit runtime with zero external API server overhead. It maintains dual-mode persistence, storing structured records in local SQLite tables and NetworkX directed graphs, while providing live Cypher query synchronization to cloud or on-premise Neo4j database instances. A one-click case dossier generator compiles all findings into a structured Markdown report, drastically reducing investigation lead time from days to minutes.
Conventional Large Language Model (LLM) applications implement single-prompt architectures. When fed long, unstructured case files, monolithic prompts suffer severe context degradation, hallucinate fabricated connections, and fail to isolate subtle logical contradictions. Furthermore, pure text-based LLMs cannot directly perceive video files without expensive cloud-based multimodal APIs, which can violate evidence privacy requirements. The primary goal of Sentinel AI is to design and implement an agentic multi-agent architecture where discrete, specialized intelligence agents collaborate over a structured state machine, combining local computer vision perception with explainable deductive reasoning. **Perception Scope:** Automated ingestion and entity detection for CCTV videos (`.mp4`) using YOLOv8, processing footage at 1 FPS to balance detection fidelity with CPU efficiency. **Text & Statement Scope:** Parsing multi-source witness testimonies, police reports, and interrogation transcripts with structured entity and relationship extraction. **Reasoning Scope:** Automated timeline reconstruction, contradiction identification, and multi-factor suspect ranking based on Motive, Means, and Opportunity (MMO). **Persistence Scope:** Local SQLite relational storage, in-memory NetworkX graph visualization, and optional real-time live Neo4j graph synchronization. **Operational Limitations:** Audio processing currently accepts structured transcripts or simulated audio testimonies, while high-resolution multi-stream 4K video feeds benefit from GPU acceleration.

</p>
<p>
  <a href="https://github.com/jay2244-byte/Sentinel_AI_MACIS/blob/main/Suretrust%20Project%20Document.pdf" target="_blank"><strong>→ View Full Project Report</strong></a>
</p>



<hr style="height:1px; border-top:1px solid #ccc; width:80%;" />


## **References**

- [SURE Trust Website](https://www.suretrustforruralyouth.com/)
- [LangGraph Framework Docs](https://langchain-ai.github.io/langgraph/)
- [Ultralytics YOLOv8 Documentation](https://docs.ultralytics.com/)
- [Neo4j Python Driver Manual](https://neo4j.com/docs/python-manual/current/)
---


## **Learnings from LST and SST**

LST and SST sessions helped me develop essential professional skills alongside technical coding. I learned methodologies for task scheduling, project management (structuring 60-day roadmaps), and collaborative research. These sessions helped me understand how to compile case files, write technical documentation, and explain complex multi-agent architectures to stakeholders.
---

## **Community Services**



During my internship period, I participated in multiple community-oriented activities to support social development, environmental sustainability, and assistance programs in my local area.

### **Activities Involved**
<!-- add the location where you given -->

  
 <!-- add the location where you have panted -->
- **Tree Plantation Drive** – Participated by planting trees and contributing to environmental improvement.

  <!-- add the location where you helped -->
- **Helping Elder Citizens** – Assisted two elderly individuals with simple daily tasks and provided support where needed. 

<!-- you can write impacts according to your experience in your words-->

### **Impact / Contribution**

- Helped create a supportive environment during the blood donation camp. <!-- add the location where you given -->
- Actively participated in promoting a greener and cleaner surroundings.
- Offered personal assistance to elder citizens, strengthening community bonds.
- Improved skills in communication, coordination, and social responsibility.

### **Photos**

<!-- add your photos below -->
<!-- change url below with your image urls (inside  src='')-->



<div align="center">
<img src="https://github.com/jay2244-byte/Sentinel_AI_MACIS/blob/main/community%20services/Donation%20collage-overlay.jpg">
<img src="https://github.com/jay2244-byte/Sentinel_AI_MACIS/blob/main/community%20services/tree%20plantation-overlay.jpg">
<img src="https://media.licdn.com/dms/image/v2/D561FAQEJNBia4UCa5w/feedshare-document-images_800/B56Zm5b6SJJkAg-/3/1759752731458?e=1766016000&v=beta&t=yWaunKdRdLUKBLbmM3UjRYYz-_GSCfWEQ3_R7dW0xLM" alt="Community Service Photo 3" width="30%">
</div>

---

## **Certificate**

The internship certificate serves as an official acknowledgment of the successful completion of my training period. It will be issued by the organization upon fulfilling all required tasks and meeting the performance expectations of the program. The certificate validates the skills, experience, and contributions made during the internship.

<!-- add your certificate image url below (inside src='')-->

<p align="center">
<img src="https://github.com/Lord-Rahul/Practice-Programs/blob/main/react/1/public/Gemini_Generated_Image_a6w8rda6w8rda6w8.png?raw=true" alt="Internship Certificate" width="80%">
</p>

---

## **Acknowledgments**

- [Sir Prujith Radhakrishnan](https://www.linkedin.com/), Course Mentor - SURE Trust

- [Prof. Radhakumari Challa](https://www.linkedin.com/in/prof-radhakumari-challa-a3850219b) , Executive Director and Founder - [SURE Trust](https://www.suretrustforruralyouth.com/)


</div>

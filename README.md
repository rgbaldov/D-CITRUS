# Digital Twin-Integrated Citrus Sorting and Packaging System (D-CITRUS)

**Prepared by:**  

[Renann G. Baldovino, PhD](https://www.dlsu.edu.ph/colleges/gcoe/academic-departments/manufacturing-engineering-management/faculty-profile/renann-baldovino/)  
**[Department of Manufacturing Engineering and Management, De La Salle University](https://www.dlsu.edu.ph/colleges/gcoe/academic-departments/manufacturing-engineering-management/)**  

[Angelino A. Pimentel, MSc, PECE](https://scholar.google.com/citations?user=rPcj5CMAAAAJ&hl=en)  
**[School of Engineering, Architecture and Information Technology, Saint Mary's University](https://smu.edu.ph/academics/school-of-engineering-architecture-and-information-technology/)**

The project introduces **D-CITRUS**, a smart manufacturing framework designed to enhance citrus post-processing. By integrating **_digital twin_** technology, the system creates a virtual replica of the sorting and packaging process, enabling _real-time monitoring_, _simulation_, and _optimization_. **D-CITRUS** aims to improve accuracy in fruit classification, reduce waste, and streamline packaging operations while ensuring product quality. The system promotes efficiency, sustainability, and cost-effectiveness in citrus manufacturing. Ultimately, **D-CITRUS** provides a scalable solution for modernizing agricultural post-processing, aligning with the shift toward Industry 4.0 and intelligent food production systems.

## Session 1: Robotics Foundations & Evolution
```mermaid
flowchart LR
    A[Raw Citrus Fruits] --> B[Sensors & Data Capture]
    B --> C[Digital Twin Layer: Virtual Citrus Model]
    C --> D[AI Processing & Analytics]
    D --> E[Automated Sorting]
    D --> F[Smart Packaging]
    E --> G[Output: Graded Citrus]
    F --> H[Output: Packaged Citrus]

    %% Feedback loop
    G -.-> C
    H -.-> C

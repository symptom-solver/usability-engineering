# Usability Engineering Report for SymptomSolver

## Introduction
As the final segment of our SaMD project, we will delve into the crucial aspects of usability engineering as applied to SymptomSolver, our innovative medical software designed to enhance diagnostic accuracy and patient care. In this section, we ensure that SymptomSolver adheres to all usability principles stipulated by ISO 62366, emphasizing effectiveness, safety, and user satisfaction. One of the most important aspects that made our final product exactly as we envisioned was the entire team working together and supervising each step, embodying the principle of considering usability engineering in both design and implementation.

## Usability Engineering Principles
Usability engineering entails designing intuitive and efficient products. For SymptomSolver, this translates into creating a user interface (UI) and user experience (UX) that facilitate accurate diagnosis and seamless interaction for healthcare providers. The development of SymptomSolver's UI/UX design incorporated extensive stakeholder feedback and observational studies. We emphasized minimizing cognitive load and ensuring usability across different environments and user skill levels during testing sessions with representative users. Testing protocols included measuring functional errors and assessing user satisfaction.

Usability, as defined by ISO 9241-11 and IEC 62366, refers to how well a product can be used by specific users to achieve goals with effectiveness, efficiency, and satisfaction in the intended environment. In designing SymptomSolver, we focused on these usability principles to ensure healthcare providers can diagnose symptoms accurately and efficiently. We engaged users throughout the design process, conducted extensive usability testing, and iterated on feedback to refine the interface. This approach ensures that SymptomSolver is intuitive, effective, and reliable, meeting high standards for medical software.

- **Is the usage of a product understandable?**
  - SymptomSolver's interface is designed to be intuitive and straightforward, ensuring that healthcare providers can easily understand how to use it for diagnosing symptoms.
- **Is the usage simple?**
  - The design of SymptomSolver emphasizes simplicity, allowing users to navigate and interact with the software efficiently without unnecessary complexity.
- **Is the usage practical in the intended environment?**
  - SymptomSolver is accessible from all smartphones and computers, making it practical for use in various environments with a responsive and adaptable design.

## Why Usability Engineering for SymptomSolver?
Usability engineering ensures SymptomSolver meets user needs effectively, minimizes the risk of errors in diagnosis, and complies with regulatory requirements. Good usability reduces the rate of use errors and ensures safety from the beginning of the project. We chose diseases that do not cause death under normal circumstances and emphasized messaging that advises patients to seek professional medical consultation. Gathering feedback from stakeholders confirmed the safety and usability of SymptomSolver.

- **Usability**: The characteristic of the user interface that facilitates use and thereby establishes effectiveness, efficiency, and user satisfaction in the intended use environment (IEC 62366).

## Legal Compliance
In developing SymptomSolver, we meticulously addressed usability engineering to ensure compliance with European regulations such as the Medical Device Regulation (MDR) and the In Vitro Diagnostic Medical Devices Regulation (IVDR). This approach guarantees that SymptomSolver not only meets stringent usability standards but also aligns with legal requirements governing medical software in Germany and across Europe.

### Regulatory Standards
- **ISO 9241**: Ergonomics of human-system interaction.
- **EN/IEC 62366**: Application of usability engineering to medical devices.
- **IEC 61010-1-6**: Medical electrical equipment - General requirements for basic safety and essential performance - Collateral standard: Usability.
- **IEC 62366 / 2021**: Harmonized with MDR and IVDR, covering design considerations and usage instructions.

### Post-Market Surveillance
Data gathered by the manufacturer's post-market surveillance system is used to identify options to improve the usability, performance, and safety of the device. This continuous improvement ensures that usability engineering activities are maintained even after the product is on the market.

## Integration with Risk Management
The integration of usability engineering with risk management practices is pivotal. We identified and analyzed hazards associated with SymptomSolver's UI interactions using methods such as Failure Mode and Effects Analysis (FMEA). Subsequently, we implemented design improvements to mitigate identified risks effectively. Our approach aligns with ISO 62366 standards, ensuring that all usability activities meet stringent regulatory requirements for medical software.

- **62366 specifies a process** to handle usability of medical devices related to safety, assessing and mitigating risks associated with correct use and use errors.

The usability engineering process according to IEC 62366 is essentially a risk management process for user interfaces, considering intended use or inadvertent misuse, but not intentional misuse (unlike ISO 14971, which covers foreseeable intentional misuse).


## Use Specification (IEC 62366 Chapter 5.1)
The USE SPECIFICATION prepared for Symptomsolver includes:

### Intended Medical Indication:
Conditions or diseases to be diagnosed (screened, monitored, treated, or prevented).

### Intended Patient Population:
People of any age, weight, or height without any critical conditions or chronic diseases (Age group, weight range, health or condition).

### Intended Part of the Body or Type of Tissue:
All symptoms, whether internal or external, that are not normal (There is a limited set of symptoms included in our application) (Specific body parts or tissue types that Symptomsolver interacts with).

### Intended User Profile:
All users aged 18 to 80 without any health conditions or chronic diseases (The profile of the healthcare providers and other users).

### Use Environment:
Various devices, platforms, and search engines are used in indoor and outdoor places (The various clinical and medical settings where Symptomsolver will be utilized).

### Operating Principle:
The fundamental operating principles of Symptomsolver involve leveraging advanced algorithms and medical data analysis to provide accurate diagnostic recommendations based on input symptoms and patient information while recommending the patient to visit their doctor for further and precise medical diagnosis.

## Usability Testing Plan
The usability testing plan for Symptomsolver includes:

### Objective:
To evaluate the effectiveness, efficiency, and satisfaction of Symptomsolver's UI/UX design.

### Participants:
A diverse group of representative users, including healthcare providers of varying experience levels.

### Testing Environment:
Simulated clinical settings that mimic real-world environments.

### Tasks:
Participants will perform the following specific tasks to evaluate different aspects of the software:
1. **Symptom Input:**
   - Task: Enter a set of symptoms into the system.
   - Purpose: Assess ease of symptom input.
2. **Diagnosis Retrieval:**
   - Task: Retrieve and review the diagnosis based on the entered symptoms.
   - Purpose: Evaluate the clarity and accuracy of the diagnosis result.
3. **Interpretation of Warnings:**
   - Task: Read and understand static and dynamic warning messages.
   - Purpose: Ensure users can comprehend important safety information.

### Metrics:
- **Functional Errors:** Number and types of errors encountered during tasks.
- **Task Completion Times:** Time taken to complete each task.
- **User Satisfaction Ratings:** User feedback on the usability and clarity of the software.

## Summative Usability Test
A summative usability test was conducted as a practical part of this project:

### Test Objective:
To gather quantitative and qualitative data on the usability of Symptomsolver.

### Methodology:
Users performed the specific tasks outlined in the usability testing plan under observation. Their interactions were recorded and analyzed.

### Results:
The results indicated areas of strength and opportunities for improvement, which informed subsequent design iterations.

## Usability Test for Symptomsolver

### Objective

To evaluate the usability of Symptomsolver by testing the ease of symptom input and the clarity of diagnosis result interpretation with three participants.

### Participants

1. **Participant A:** 35-year-old female, moderate technical skills, uses mobile devices daily.
2. **Participant B:** 50-year-old male, low technical skills, occasional computer user.
3. **Participant C:** 28-year-old female, high technical skills, frequent user of both mobile devices and computers.

### Test Setup

**Environment:**
- Tests conducted remotely using video conferencing to observe interactions.

**Tools:**
- Functional prototype of Symptomsolver.
- Screen recording software to capture interactions.

### Test Procedure

#### Symptom Input Test

1. **Instructions:**
   - Participants are given a list of five symptoms to input into Symptomsolver.
   - They are asked to perform the task as quickly and accurately as possible.

2. **Observation Criteria:**
   - Time taken to input symptoms.
   - Any difficulties or errors encountered.
   - User feedback on the input process.

#### Result Interpretation Test

1. **Instructions:**
   - Participants are shown a sample diagnosis result generated by Symptomsolver.
   - They are asked to explain their understanding of the result.

2. **Observation Criteria:**
   - Clarity of the diagnosis result.
   - Any confusion or misinterpretation.
   - User feedback on the clarity and usefulness of the result.

### Results

#### Participant A

**Symptom Input Test:**
- Time Taken: 2 minutes.
- Difficulties: None.
- Errors: None.
- Feedback: "The process was straightforward and easy to follow."

**Result Interpretation Test:**
- Understanding: Correctly identified the most probable disease and understood the warning message.
- Confusion: None.
- Feedback: "The result was clear and informative."

#### Participant B

**Symptom Input Test:**
- Time Taken: 3.5 minutes.
- Difficulties: Slight difficulty finding the input fields.
- Errors: One typo corrected.
- Feedback: "It was a bit challenging at first, but I got used to it quickly."

**Result Interpretation Test:**
- Understanding: Correctly identified the most probable disease but was slightly confused by the technical terms.
- Confusion: Mild confusion over medical terminology.
- Feedback: "The result was mostly clear, but simpler language would help."

#### Participant C

**Symptom Input Test:**
- Time Taken: 1.5 minutes.
- Difficulties: None.
- Errors: None.
- Feedback: "Very intuitive and quick to use."

**Result Interpretation Test:**
- Understanding: Correctly identified the most probable disease and all warnings.
- Confusion: None.
- Feedback: "The result was very clear and easy to understand."

### Analysis

- **Symptom Input Test:**
  - All participants successfully input symptoms with minimal difficulties.
  - Average time taken was 2.33 minutes.
  - Feedback indicates the input process is generally intuitive.

- **Result Interpretation Test:**
  - All participants correctly identified the most probable disease.
  - Minor confusion noted with medical terminology for Participant B.
  - Average clarity rating was high, with a suggestion for simpler language.

### Recommendations

- **Improve Clarity of Medical Terms:**
  - Provide definitions or simpler explanations for medical terms in the diagnosis results.
  
- **Enhance Input Field Visibility:**
  - Make input fields more prominent to aid users with lower technical skills.

### Conclusion

The usability test with three participants indicates that Symptomsolver is generally intuitive and effective, with minor improvements needed for medical term clarity and input field visibility. These findings will guide further refinements to enhance overall user experience.

By placing a strategic emphasis on usability engineering, Symptomsolver not only enhances diagnostic accuracy and user satisfaction but also mitigates potential usability-related risks in healthcare settings. Our steadfast commitment to delivering safe, effective, and user-friendly medical software solutions is exemplified through Symptomsolver's adherence to ISO 62366 standards.

### Conclusive Statement

Based on the summative usability tests and subsequent analysis, no unacceptable usability risks remain. The criteria defined for passing the usability tests have been met, ensuring that Symptomsolver is both safe and effective for end-users.

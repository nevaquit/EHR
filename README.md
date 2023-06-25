# EHR
Electronic Health Records with AI enhancement and Blockchain Security (HIPAA compliant)
User Stories for Sprint 1:

As a developer, I want to set up the development environment with Solidity, Remix, Ethereum, and Ganache, so that I can start developing the smart contract.
As a developer, I want to create the basic smart contract structure and data structures (e.g., structs for Patient, Doctor, and Medicine), so that I can implement the user registration functions for both patients and doctors.
As a patient, I want to be able to register my account on the platform, so that I can access my medical records.
As a doctor, I want to be able to register my account on the platform, so that I can access my patients' medical records.
As a developer, I want to implement the access control mechanisms (e.g., onlyDoctor and onlyPatient modifiers), so that only authorized users can access the system.
As a tester, I want to ensure that the user registration functionality and access control are working as expected, so that we can move on to the next sprint.


User Stories for Sprint 2:

As a doctor, I want to be able to add and update patient data (e.g., addDisease, updatePatientDetails), so that I can provide better care to my patients.
As a patient, I want to be able to view my medical records on the platform, so that I can keep track of my health.
As a developer, I want to implement error handling and appropriate access control for patient record management functions, so that the system remains secure and reliable.
As a tester, I want to ensure that the patient record management functionality is working as expected, so that we can move on to the next sprint.

User Stories for Sprint 3:

As a doctor, I want to be able to add and prescribe medicines (addMedicine and prescribeMedicine), so that I can provide better care to my patients.
As a patient, I want to be able to view details of the prescribed medicines on the platform, so that I can be informed about my treatment.
As a developer, I want to implement error handling and access control for medicine-related functions, so that the system remains secure and reliable.
As a tester, I want to ensure that the medicine management and prescription functionality is working as expected, so that we can move on to the next sprint.


User Stories for Sprint 4:

As a doctor, I want to be able to view my patients' data and prescribed medicines (viewPatientDataByDoctor and viewPrescribedMedicineToPatient), so that I can provide better care to my patients.
As a patient, I want to be able to view my doctor's details on the platform, so that I can be informed about my treatment.
As a developer, I want to implement error handling and access control for doctor-patient interaction functions, so that the system remains secure and reliable.
As a tester, I want to ensure that all functionalities are working as expected, so that we can deploy the final product to the Ethereum network and host the dApp on a suitable blockchain instance.



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Sprint 1: Basic Setup and User Registration - Scheduling
Objective: Set up the development environment, create the smart contract structure, and implement user registration functions for both patients and doctors.

Tasks:

Set up the development environment with Solidity, Remix, Ethereum, and Ganache.
Create the basic smart contract structure and data structures (e.g., structs for Patient, Doctor, and Medicine).
Implement the user registration functions for both patients and doctors (registerPatient and registerDoctor).
Implement the access control mechanisms (e.g., onlyDoctor and onlyPatient modifiers).
Test user registration functionality and access control.
Deliverable: A functional smart contract with user registration for patients and doctors.

Sprint 2: Patient Records and Disease Management

Objective: Implement functions for managing patient records and diseases, as well as viewing patient data.

Tasks:

Implement the functions to add and update patient data (e.g., addDisease, updatePatientDetails).
Implement the function to view patient data (viewPatientData).
Implement error handling and appropriate access control for these functions.
Test patient record management functionality.

Deliverable: A smart contract with functions to manage patient records and diseases.

Sprint 3: Medicine Management and Prescription
Objective: Implement functions for managing medicines and prescriptions.

Tasks:

Implement the functions to add and prescribe medicines (addMedicine and prescribeMedicine).
Implement the function to view medicine details (viewMedicineDetails).
Implement error handling and access control for medicine-related functions.
Test medicine management and prescription functionality.
Deliverable: A smart contract with functions for medicine management and prescription.

Sprint 4: Doctor-Patient Interactions and Final Integration
Objective: Implement functions for doctor-patient interactions and integrate all functionalities into the final product.

Tasks:

Implement the functions for doctors to view patient data and prescribed medicines (viewPatientDataByDoctor and viewPrescribedMedicineToPatient).
Implement the function to view doctor details (viewDoctorDetails).
Implement error handling and access control for doctor-patient interaction functions.
Test and integrate all functionalities.
Deploy the smart contract to the Ethereum network and host the dApp on a suitable blockchain instance.

Deliverable: A fully functional blockchain-based EHR solution with proper access control, error handling, and adherence to best practices.


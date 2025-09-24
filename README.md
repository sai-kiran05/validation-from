### **Experiment 10: Form Validation** (CO4)  
- **Objective:** Validate form fields before submission.  
- **Task:** Validate email format and password length.  
- **Pseudo Code:**  
Step 1: Create error state variables → emailError, passwordError
Step 2: On form submit:
- If email does not match regex → set emailError
- If password length < 6 → set passwordError
Step 3: Display error messages below inputs
Step 4: If no errors → show "Form Submitted Successfully

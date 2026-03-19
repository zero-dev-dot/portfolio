# 📄 XP User Stories + Test Cases  
## 🌐 Astro Portfolio Website

---

## 🧑‍💻 Story 1: Render Homepage

**Story:**  
As a visitor, I want to see the homepage so that I can understand who the developer is.

### Acceptance Tests
- Homepage loads successfully  
- Name, title, subtitle visible  

### Test Cases
| ID | Test Case | Input | Expected Output |
|----|----------|------|----------------|
| TC1.1 | Load homepage | Open URL | Page renders successfully |
| TC1.2 | Check content | None | Name, title, subtitle visible |
| TC1.3 | Performance test | Load page | Load time < 3s |

---

## ☁️ Story 2: Cloud Navigation

**Story:**  
As a user, I want to click cloud buttons so that I can navigate between sections.

### Acceptance Tests
- Clicking cloud scrolls to section  
- Hover animation works  

### Test Cases
| ID | Test Case | Input | Expected Output |
|----|----------|------|----------------|
| TC2.1 | Click About cloud | Click button | Scroll to About section |
| TC2.2 | Hover cloud | Mouse hover | Animation visible |
| TC2.3 | Click Projects | Click button | Scroll to Projects |

---

## 📱 Story 3: Responsive Layout

**Story:**  
As a mobile user, I want a responsive layout so that I can use the site on my phone.

### Acceptance Tests
- Layout adapts to screen size  

### Test Cases
| ID | Test Case | Input | Expected Output |
|----|----------|------|----------------|
| TC3.1 | Mobile view | Width < 768px | Layout stacks vertically |
| TC3.2 | Tablet view | Width 768–1024px | Adjusted layout |
| TC3.3 | Text readability | Any size | Text readable |

---

## 👤 Story 4: About Section

**Story:**  
As a visitor, I want to read about the developer so that I know their background.

### Acceptance Tests
- Bio and image visible  

### Test Cases
| ID | Test Case | Input | Expected Output |
|----|----------|------|----------------|
| TC4.1 | Load About | Scroll to section | Bio displayed |
| TC4.2 | Image load | Open section | Image visible |

---

## 🛠️ Story 5: Skills Section

**Story:**  
As a recruiter, I want to see skills so that I can evaluate expertise.

### Acceptance Tests
- Skills list displayed  

### Test Cases
| ID | Test Case | Input | Expected Output |
|----|----------|------|----------------|
| TC5.1 | Load Skills | Scroll | Skills visible |
| TC5.2 | UI check | None | Icons/progress bars visible |

---

## 💼 Story 6: Experience Section

**Story:**  
As a recruiter, I want to view experience so that I can assess work history.

### Acceptance Tests
- Timeline displayed  

### Test Cases
| ID | Test Case | Input | Expected Output |
|----|----------|------|----------------|
| TC6.1 | Load timeline | Scroll | Timeline visible |
| TC6.2 | Entry check | None | Role, company, duration shown |

---

## 🚀 Story 7: Projects Section

**Story:**  
As a visitor, I want to see projects so that I can evaluate developer work.

### Acceptance Tests
- Project cards visible  

### Test Cases
| ID | Test Case | Input | Expected Output |
|----|----------|------|----------------|
| TC7.1 | Load projects | Scroll | Cards displayed |
| TC7.2 | Click GitHub link | Click link | Opens repo |
| TC7.3 | Check content | None | Title & description shown |

---

## 📬 Story 8: Contact Form

**Story:**  
As a visitor, I want to send a message so that I can contact the developer.

### Acceptance Tests
- Form submission works  

### Test Cases
| ID | Test Case | Input | Expected Output |
|----|----------|------|----------------|
| TC8.1 | Submit valid form | Valid data | Success message |
| TC8.2 | Invalid email | Wrong format | Error message |
| TC8.3 | Empty fields | Blank | Submission blocked |

---

## 🔐 Story 9: Input Validation

**Story:**  
As a system, I want to validate input so that invalid data is rejected.

### Acceptance Tests
- Invalid data blocked  

### Test Cases
| ID | Test Case | Input | Expected Output |
|----|----------|------|----------------|
| TC9.1 | Empty input | Blank fields | Error shown |
| TC9.2 | Invalid email | "abc" | Validation error |

---

## ⚡ Story 10: Performance

**Story:**  
As a user, I want fast loading so that I have a smooth experience.

### Acceptance Tests
- Fast load time  
- Minimal JS  

### Test Cases
| ID | Test Case | Input | Expected Output |
|----|----------|------|----------------|
| TC10.1 | Load test | Open page | < 3s load |
| TC10.2 | JS check | Inspect | Only islands load JS |

---

## 🎨 Story 11: Animations

**Story:**  
As a user, I want animations so that the UI feels engaging.

### Acceptance Tests
- Smooth animation  

### Test Cases
| ID | Test Case | Input | Expected Output |
|----|----------|------|----------------|
| TC11.1 | Load animation | Open page | Clouds float |
| TC11.2 | Performance | Run animation | No lag |

---

## 🚀 Story 12: Deployment

**Story:**  
As a developer, I want to deploy the site so that it is accessible online.

### Acceptance Tests
- Site accessible online  

### Test Cases
| ID | Test Case | Input | Expected Output |
|----|----------|------|----------------|
| TC12.1 | Open URL | Visit link | Site loads |
| TC12.2 | HTTPS check | Open site | Secure connection |

---

## ✅ Summary
- XP-style user stories  
- Acceptance tests  
- Detailed test cases (TDD-ready)
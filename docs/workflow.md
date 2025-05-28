# ICPC Web Platform Workflow Documentation

## 1. Core User Flows

### 1.1 Main Entry Points (index.html)
- Three primary pathways:
  1. **Tailored Information**
     - Cancer-specific resources
     - Support services
     - Questions and guidelines
  2. **Guidelines**
     - Cancer type selection
     - Language options (English/Hindi)
     - Downloadable PDFs
  3. **Treatment Options**
     - Cancer center locator
     - Treatment protocols
     - Support resources

### 1.2 Cancer Center Search Flow (cancer-center/)
1. User selects cancer type (choose-type.html)
   - Lung Cancer
   - Oral Cancer
   - Breast Cancer
2. Enters location details (cancer-center-form.html)
   - Country (India)
   - State (UP/Bihar)
   - City
   - Pincode
3. Views search results (show-cancer-centers.html)
   - Hospital listings
   - Contact information
   - Facility details

### 1.3 Information Access Flow (tailored-information/)
1. Support for Rare & Hard to Treat Cancers
   - Cancer Centers Directory
   - NGO Connections
   - Community Forum
   - Financial Support Programs
2. Cancer Management Resources
   - Screening Information
   - Risk Assessment
   - Questions Database

### 1.4 Questions & Resources Flow (questions-to-ask/)
1. Question Categories (questions-category.html)
   - Risk Assessment
   - Insurance & Coverage
   - Screening Process
   - Test Results
   - Biopsy Information
2. Resource Directory (resources.html)
   - Support Organizations
   - Educational Materials
   - Research Institutions

## 2. Support Systems

### 2.1 Interactive Assistance
- AI-based Chatbot
  - Navigation assistance
  - Quick answers
  - Resource suggestions
- Human Assistant Connection
  - Expert consultation
  - Personal support

### 2.2 Language Support
- Bilingual Content
  - English
  - Hindi
- Downloadable Resources
  - Guidelines
  - Information packets
  - Forms

## 3. Data Structure

### 3.1 Hospital Database (cancer_hospitals_bihar_up.json)
- State-wise organization
- City-level categorization
- Facility details:
  - Name
  - Address
  - Contact information
  - Services offered

### 3.2 Questions Database (lung_cancer_questions.json)
- Categorized questions:
  - Screening
  - Test results
  - Biopsies
- Structured answers
- Multi-language support

## 4. Technical Implementation

### 4.1 Navigation Structure
- Global header
- Persistent navigation bar
- Back button system
- Breadcrumb trails

### 4.2 User Interface Elements
- Card-based layouts
- Dropdown menus
- Search forms
- Results display
- Interactive elements

### 4.3 Responsive Design
- Mobile-friendly layouts
- Adaptive content
- Touch-friendly interfaces

## 5. User Support Features

### 5.1 Educational Resources
- Guidelines documents
- Informational articles
- FAQ sections
- Video resources

### 5.2 Community Support
- Forums
- Support groups
- NGO connections
- Financial assistance

## 6. Integration Points

### 6.1 External Services
- AI prediction tool
- Expert connection system
- Government scheme links
- Research institution connections

### 6.2 Partner Organizations
- SHUATS
- ICPC
- MOHFW
- ICMR
- Other healthcare institutions

## 7. Future Expansion Points

### 7.1 Planned Features
- Additional cancer types
- More regional coverage
- Enhanced AI integration
- Mobile application
- Telemedicine services

### 7.2 Scalability Considerations
- Database expansion
- Multi-language support
- Regional customization
- Service integration

## 8. User Journey Mapping

### 8.1 Patient Path
1. Initial landing
2. Cancer type selection
3. Resource access
4. Support connection
5. Treatment center location
6. Ongoing support

### 8.2 Healthcare Provider Path
1. Guidelines access
2. Patient resources
3. Facility registration
4. Network connection
5. Research access

## 9. Content Management

### 9.1 Resource Organization
- Cancer-specific content
- General information
- Support services
- Guidelines and protocols

### 9.2 Update Procedures
- Content revision
- Database updates
- Resource verification
- Link maintenance

# 🚀 Company Registration Portal Challenge

## Overview
Build a modern SaaS company registration portal using Next.js 14 with the App Router and Shadcn/UI components. This challenge simulates a real-world scenario where companies need to register for a B2B SaaS platform.

### 🎯 Challenge Context
Imagine you're building the onboarding flow for a B2B SaaS platform that helps companies manage their digital transformation. The first step is creating a robust and user-friendly company registration form that validates and collects essential company information.

## 🛠 Technical Requirements

### Frontend Stack
- Next.js 14 (App Router)
- Shadcn/UI Components
- TypeScript
- React Hook Form (recommended)
- Zod for validation (recommended)

### Backend Stack
- Express.js
- TypeScript (recommended)

### Required Features

#### Company Registration Form
The form should collect the following information:
- Company Name
- CNPJ (Brazilian Company Registration Number)
- CEP (Postal Code)
- Complete Address
- Company Email
- Titular Information:
  - Name
  - Email
  - Position
  - CPF (Brazilian Individual Taxpayer Registry)

#### Integration Requirements
1. **CNPJ Auto-fill**
   - Integrate with Brasil API (https://brasilapi.com.br/)
   - Auto-fill company name when CNPJ is provided
   - Validate CNPJ format and existence

2. **Address Auto-complete**
   - Integrate with Brasil API CEP endpoint
   - Auto-fill address fields when CEP is provided
   - Handle invalid CEP scenarios

3. **Backend Integration**
   - Create an Express.js API endpoint to receive the form data
   - Implement proper validation
   - Return appropriate success/error responses
   - Status code 200 for successful submissions

## 🎨 UI/UX Requirements
- Implement a multi-step form for better user experience
- Show loading states during API calls
- Provide clear validation feedback
- Implement error handling with user-friendly messages
- Make the form responsive for all screen sizes

## 📋 Evaluation Criteria
1. **Code Quality**
   - Clean, well-organized code
   - TypeScript usage
   - Proper error handling
   - Code reusability

2. **UI/UX**
   - Form accessibility
   - Responsive design
   - Loading states
   - Error states

3. **Technical Implementation**
   - Proper form validation
   - API integration
   - Data handling
   - TypeScript types/interfaces

## 🚦 Getting Started

1. Fork this repository
2. Create a new branch with your name: \`git checkout -b feature/your-name\`
3. Install dependencies
4. Implement the solution
5. Test thoroughly
6. Create a Pull Request
7. Send an email to jaison@onbloc.com.br with:
   - Subject: "Company Registration Challenge - [Your Name]"
   - Link to your forked repository
   - Any additional notes or comments about your implementation

## 📝 Submission Guidelines

1. Your solution must include:
   - Complete frontend implementation
   - Backend API implementation
   - README with setup instructions
   - Any necessary environment variables (provide examples)

2. Documentation:
   - Include setup instructions
   - List any assumptions made
   - Describe your technical decisions
   - Explain any additional features (if implemented)

## ⚙️ Bonus Points

- Unit tests implementation
- E2E tests
- Docker configuration
- CI/CD setup
- Additional validations
- Animations and transitions
- Performance optimizations
- Accessibility considerations

## 🤔 Questions?

If you have any questions about the challenge, feel free to reach out to jaison@onbloc.com.br

Good luck! 🍀

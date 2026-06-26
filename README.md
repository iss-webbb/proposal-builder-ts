# Quote / Proposal Builder (TypeScript Edition)

A modern, type-safe multi-step form application for collecting client information and generating professional proposals. Built with React, TypeScript, and Vite.

## 🎯 Features

- **Multi-step Form**: 3-step process (Customer Info → Line Items → Preview)
- **Type-Safe**: Full TypeScript support for reliability
- **Dynamic Line Items**: Add, edit, and remove services with quantities and prices
- **Automatic Calculations**: Real-time total calculations
- **Local Storage Persistence**: Your data persists across sessions
- **Professional Preview**: Generate formatted proposal previews
- **Form Validation**: Input validation for customer and line item data
- **Modal System**: Intuitive modal interface for managing items

## 🛠 Tech Stack

- **React** - UI library
- **TypeScript** - Type-safe JavaScript
- **Vite** - Build tool & dev server
- **CSS** - Styling

## 📦 Installation

```bash
git clone https://github.com/iss-webbb/proposal-builder-ts.git
cd proposal-builder-ts/ts/ts
npm install
npm run dev
```

## 🚀 Getting Started

1. Navigate to the project folder
2. Install dependencies with `npm install`
3. Start the dev server with `npm run dev`
4. Open [http://localhost:5173](http://localhost:5173) in your browser

## 📁 Project Structure

```
ts/ts/
├── src/
│   ├── components/        # React components
│   ├── customhooks/       # Custom React hooks
│   ├── App.tsx            # Main app component
│   └── App.css            # Styles
├── package.json
├── tsconfig.json
└── vite.config.ts
```

## 🎓 Key Concepts Demonstrated

- **React Hooks**: useState, useEffect
- **Custom Hooks**: useProposal for state management
- **TypeScript Types**: Interfaces and type definitions
- **Component Composition**: Reusable, typed components
- **Local Storage**: Persistent data storage with type safety
- **Form Handling**: Multi-step form logic
- **State Management**: Complex state with proper typing

## 💾 How It Works

1. **Step 1**: Enter customer information (name, email, company, etc.)
2. **Step 2**: Add line items with service details, quantities, and prices
3. **Step 3**: Review and export the complete proposal

All data is automatically saved to localStorage with type safety!

## 🔮 Future Improvements

- Export to PDF functionality
- Email integration
- Template customization
- Dark mode support
- Mobile responsiveness improvements
- Advanced form validation with Zod

## 📝 Notes

This is a learning project demonstrating React with TypeScript and multi-step form patterns.

---

**Want the JavaScript version?** Check out [proposal-builder](https://github.com/iss-webbb/proposal-builder)

# Rightside, personal finance app

A comprehensive web application for managing personal finances, tracking expenses, and monitoring cashflow. Built with React, TypeScript, and Supabase.

**Live Demo**: https://rightside-loveable.vercel.app/

## Features

### Cashflow Management
- Interactive cashflow chart with date range filtering
- Transaction tracking for both income and expenses
- Category-based expense organization
- Financial insights and personalized advice
- CSV upload support for bulk transaction imports

### Credit Card Management
- Track multiple credit cards
- Monitor credit limits and balances
- Track APR, annual fees, and other card details
- Due date tracking and minimum payment information

### Financial Goals
- Create and track multiple financial goals
- Monitor progress with visual progress bars
- Track savings against target amounts
- Categorize goals (Savings, Large Purchase, Travel, etc.)
- View total savings progress across all goals

### Budgeting Tools
- Create and manage expense categories
- Color-coded category system
- Transaction categorization
- Spending insights and analysis

### Alert System
- Customizable price alerts for assets
- Spending limit notifications
- Large transaction monitoring
- Push notifications and email digests

## Technology Stack

- **Frontend Framework**: React with TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Icons**: Lucide React (BadgeDollarSign, Wallet, Plus)
- **Charts**: Recharts
- **Backend**: Supabase
  - Authentication
  - PostgreSQL Database
  - Row Level Security
  - Edge Functions
  - File Storage

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Git

## CSV Import Format

### Expenses CSV Format
Required columns:
- date (MM/DD/YYYY)
- description
- amount
- category (optional)
- account_name (optional)

### Income CSV Format
Required columns:
- date (MM/DD/YYYY)
- title
- amount

## Security

- Row Level Security (RLS) policies ensure users can only access their own data
- Secure authentication handled by Supabase
- All database queries are protected by RLS policies
- File uploads are restricted to authenticated users

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

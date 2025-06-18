# Proteome App Plan

_A user-centric, excellent UX/UI general purpose health tracker_

## Vision Statement

Proteome aims to be the most intuitive and comprehensive personal health tracking platform, empowering users to take control of their health data while maintaining simplicity and elegance. Open-source and self-hostable, with optional PRO features for advanced users.

## Core MVP Features (Ultra-Simple)

### 🏥 **Medication Management**

- **Add Medications**

  - Medication name (manual entry with simple search)
  - Dosage (number field)
  - Unit (dropdown: mg, ml, tablets, capsules, drops, puffs, etc)
  - Instructions (text field)
  - Medication type (scheduled, as-needed)
  - Start Date (date picker)
  - End Date (date picker)
  - Schedule
    - Days of the week (checkboxes)
    - Times of day (time picker) - Can add multiple times

- **Edit Medications**

  - Same fields as add

- **Delete Medications**

  - One-tap "delete" button with confirmation

- **Take Medications**

  - One-tap "taken" logging
  - Simple adherence tracking (percentage)

- **Basic Reminders**
  - Users will receive a notification reminding them it's time to take whatever medication they have scheduled for that day + time at that time. I.e. if they have a scheduled medication for 10am, they will receive a notification at 10am.

### 📊 **Health Check-ins**

- **Daily Wellness**
  - Daily journal entry for wellness where users can view past days' entries
  - Optional logging of any / all of the following:
  - "How are you feeling today?" (1-10 scale)
  - Weight logging
  - Blood pressure logging
  - Temperature logging
  - Symptoms / Side Effects (text field)
  - Notes (text field)

### 👤 **Minimal Profile**

- **Essential Info Only**
  - Height, birthdate, biological sex
  - Basic allergies (text field)

### 📈 **Simple Analytics**

- **Basic Charts**
  - Weight trend line (if logged)
  - Temperature trend line (if logged)
  - Blood pressure trend line (if logged)

### 🔄 **Data Export**

- **CSV Export**
  - All medication and health data
  - Simple download functionality

## 3-Screen App Structure

### 📱 **Screen 1: Today / At a Glance**

Users will land on the /dashboard page by default as the home page of the actual application. In the top right is a date selector where users can select the date they want to view. Users can only modify data for the current day.

- **Primary Actions**
  - Medication checklist with one-tap "taken" buttons (user can revoke a taken medication and take it later, this will be a toggle button with a history of actions preserved)
  - Two tabs on medication checklist: 
    - Scheduled
    - As-Needed
  - Quick wellness check-in (1-10 scale)

### 💊 **Screen 2: Medications**

- **Medication Management**
  - List of all medications
  - Add new medication (name, dose, frequency)
  - Edit/delete existing medications
  - Toggle reminders on/off

### 📊 **Screen 3: History / Trends**

- **Simple Visualizations**
  - Weight trend (if logged)
  - Wellness mood trend
  - Export data button

## PRO Plan Features

### 🔬 Advanced Analytics

- **Deep Health Insights**
  - Predictive health trends
  - Advanced correlation analysis
  - Custom report builder
  - Data visualization customization

### 👥 Family & Care Team Management

- **Multi-User Support**
  - Family member profiles
  - Caregiver access controls
  - Healthcare provider dashboards
  - Shared medication schedules

### 🤖 AI-Powered Features

- **Smart Recommendations**
  - Medication timing optimization
  - Health pattern recognition
  - Personalized wellness suggestions
  - Automated health report generation

### 🔗 Integrations

- **Third-Party Connections**
  - Pharmacy API integration
  - Wearable device sync (Fitbit, Apple Watch)
  - EHR system compatibility
  - Telehealth platform integration

### 📋 Advanced Reporting

- **Professional Reports**
  - Healthcare provider summaries
  - Insurance claim preparation
  - Detailed medication history
  - Custom report templates

### 🛠️ Power User Features

- **API Access**
  - RESTful API for data access
  - Webhook support
  - Custom field creation
  - Bulk data operations

## Technical Architecture

### 🏗️ Open Source & Self-Hostable

- **Core Stack**

  - Next.js 14 with App Router
  - Supabase for backend services
  - TypeScript for type safety
  - Tailwind CSS for styling

- **Self-Hosting Options**
  - Docker containerization
  - One-click deployment scripts
  - Database migration tools
  - Backup/restore utilities

### 🔒 Privacy & Security

- **Data Protection**
  - End-to-end encryption for sensitive data
  - HIPAA compliance considerations
  - GDPR compliance for EU users
  - Local data storage options

## User Experience Principles

### ✨ Ultra-Simple Design

- **Minimal Cognitive Load**
  - One primary action per screen
  - No more than 3 buttons visible at once
  - Smart defaults for everything
  - Zero configuration required

### 🎨 Beautiful & Intuitive

- **Design System**
  - Consistent component library
  - Accessible color palette
  - Typography hierarchy
  - Responsive design patterns

### ⚡ Performance

- **Fast & Reliable**
  - Sub-3-second load times
  - Offline-first approach
  - Progressive loading
  - Error state handling

## Monetization Strategy

### 💰 Simple Freemium Model

- **Free Tier**: Complete MVP for individual users
- **PRO Tier ($4.99/month)**: Advanced charts, family accounts, sync
- **Self-Hosted**: Free forever with full features

### 🌟 Value Proposition

- **Free Users**: Complete personal health tracking solution
- **PRO Users**: Advanced insights, family management, professional integrations
- **Open Source**: Full code transparency, self-hosting capability

## Success Metrics

### 📈 Key Performance Indicators

- **User Engagement**

  - Daily active users
  - Medication adherence rates
  - Time spent in app
  - Feature adoption rates

- **Health Outcomes**
  - User-reported wellness improvements
  - Medication compliance scores
  - Correlation discovery success
  - Healthcare provider feedback

## Development Phases

### **Phase 1: Ultra-MVP (4-6 weeks)**

- 3-screen responsive web app
- Basic medication CRUD
- Simple reminders
- Wellness check-in
- CSV export

### **Phase 2: Polish & Analytics (2-3 weeks)**

- Charts and trends
- Better UX/UI polish
- PWA capabilities

### **Phase 3: PRO Features (4-6 weeks)**

- Advanced analytics
- Family accounts
- Enhanced features

### **Phase 4: Growth (Ongoing)**

- Mobile apps
- Integrations
- Community features

---

_This plan prioritizes user experience, simplicity, and gradual feature rollout while maintaining the open-source ethos and providing clear monetization paths._

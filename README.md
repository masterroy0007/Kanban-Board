# Kanban-Board
 Kanban Board Component

A fully functional Kanban Board View - a drag-and-drop task management system built with React, TypeScript, and Tailwind CSS.

## Live Storybook
[Storybook Deployment Link](#) <!-- Add your deployed Storybook link here -->

## Installation

```bash
npm install
npm run dev
```

To run Storybook:
```bash
npm run storybook
```

## Architecture

This Kanban Board component is built with a modular architecture following modern React best practices:

1. **Component Structure**:
   - `KanbanBoard` - Main container component
   - `KanbanColumn` - Individual column component
   - `KanbanCard` - Task card component
   - `TaskModal` - Task creation/editing modal
   - Primitives (`Button`, `Modal`, `Avatar`) - Reusable UI components

2. **State Management**:
   - Uses React's built-in useState for local state management
   - Separates concerns with custom hooks for drag-and-drop functionality

3. **Data Flow**:
   - Unidirectional data flow from parent to child components
   - Callback functions for handling user interactions
   - Immutable state updates for predictable behavior

4. **Styling**:
   - Tailwind CSS for utility-first styling
   - Responsive design for all device sizes
   - Custom CSS for specific requirements

## Features

- [x] Drag-and-drop tasks between columns
- [x] Task creation/editing with detailed modal
- [x] Responsive design for mobile, tablet, and desktop
- [x] Keyboard accessibility
- [x] Column management (collapse/expand, add tasks)
- [x] Task prioritization with color coding
- [x] Assignee avatars
- [x] Tag management
- [x] Due date tracking with overdue indicators
- [x] Empty state handling

## Storybook Stories

- Default board with sample tasks
- Empty state
- Large dataset with 50+ tasks
- Mobile responsive view
- Interactive playground

## Technologies

- React + TypeScript
- Tailwind CSS
- Storybook
- @dnd-kit/core (for drag-and-drop primitives)

## Development

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Run Storybook for component development:
   ```bash
   npm run storybook
   ```

## Folder Structure

```
src/
├── components/
│   ├── KanbanBoard/
│   │   ├── KanbanBoard.tsx
│   │   ├── KanbanBoard.stories.tsx
│   │   ├── KanbanBoard.types.ts
│   │   ├── KanbanColumn.tsx
│   │   ├── KanbanCard.tsx
│   │   └── TaskModal.tsx
│   └── primitives/
│       ├── Button.tsx
│       ├── Modal.tsx
│       └── Avatar.tsx
├── hooks/
│   └── useDragAndDrop.ts
├── utils/
│   └── task.utils.ts
└── styles/
    └── globals.css
```

## Contact

[shivamkumarroy1920@gmail.com]

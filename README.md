# Professor Ma Qing - Academic Profile Website

A modern, clean academic profile website inspired by minimalist design principles, featuring a fluid document-style layout without visual separation.

## 🎯 Design Philosophy

### **Minimalist & Professional**
Inspired by leading academic profiles, this website embraces:
- Clean white background with no card borders
- Flowing document-style layout (not separated cards)
- Simple typography hierarchy
- Collapsible sections for better content organization
- Minimal navigation for focused user experience

### **Layout Structure**

**Top Navigation (4 Items Only)**
- Home
- Research
- Publications
- Contact

**Main Content**
- Left: Profile photo (circular), name, title, and contact links
- Right: Biography, research interests, and education side-by-side

**Collapsible Sections**
All additional content sections can be expanded/collapsed:
1. Awards & Honors
2. Journal Editorship
3. Publications (default open, with tabs)
4. Research Grants
5. Doctoral Supervision
6. External Appointments

## ✨ Key Features

### **Simplified Navigation**
- Only 4 essential links in the header
- Clean, distraction-free design
- Smooth scroll to sections

### **Collapsible Content**
- Click section titles to expand/collapse
- Chevron icons indicate state
- Publications section open by default
- Reduces visual clutter while maintaining full content access

### **Fluid Document Design**
- No card borders or shadows
- Content separated by subtle dividers
- Consistent spacing throughout
- Feels like reading a single document

### **Responsive Layout**
- Circular profile photo on larger screens
- Two-column layout for Interests/Education
- Mobile-friendly collapsible navigation
- Stacks gracefully on smaller screens

## 📋 Content Sections

### Profile Area
- **Circular profile photo** (264x264px)
- Name in English and Chinese
- Professional title and affiliation
- Contact information with icons
- Social/academic profile links

### Biography
- Expandable "Read More" for full bio
- Research focus and achievements summary
- Clean paragraph formatting

### Research Interests & Education
- Side-by-side layout (desktop)
- Bullet-point research areas
- Degree information with institutions

### Collapsible Sections

#### Awards & Honors
- 13+ international and national awards
- Date and organization for each
- Simple list format with dividers

#### Journal Editorship
- 5 associate editor positions
- Bullet-point list

#### Publications (Default Open)
- **Tabs for content types:**
  - Journal Articles (16+)
  - Books (4)
  - Book Chapters (9+)
- Full citations with links
- Tags for relevant topics
- Clean dividers between items

#### Research Grants
- Project titles with funding details
- Amount, period, and funding source

#### Doctoral Supervision
- Student names and thesis titles
- Status badges (Completed/In Progress)
- Year information

#### External Appointments
- Professional roles and organizations
- Service period for each position

## 🎨 Visual Design

### Color Palette
- **Background**: Pure white (`#ffffff`)
- **Text**: Dark gray (`#111827`) for headings, medium gray (`#374151`) for body
- **Accent**: Blue (`#2563eb`) for links and interactive elements
- **Dividers**: Light gray (`#e5e7eb`)

### Typography
- **Headings**: Bold, clean sans-serif
- **Body**: Regular weight, comfortable line height
- **Links**: Blue with hover effect

### Interactive Elements
- Hover effects on buttons and links
- Smooth color transitions
- Chevron icons for expand/collapse
- Tab selection with background change

## 📱 Responsive Behavior

**Desktop (1024px+)**
- Full two-column layout
- Circular photo with contact info on left
- Wide content area on right
- Horizontal navigation in header

**Tablet (768px-1023px)**
- Slightly narrower layout
- Maintains two-column structure
- Adjusted spacing

**Mobile (<768px)**
- Single column layout
- Stacked sections
- Hamburger menu navigation
- Profile photo centered

## 🔧 Technical Stack

- **React** with TypeScript
- **Tailwind CSS** v4 (utility-first)
- **Lucide React** for icons
- Modular component architecture
- Smooth scroll behavior
- State management with React hooks

## 📂 Project Structure

```
src/
├── app/
│   ├── components/
│   │   ├── Navigation.tsx           # Simple 4-item header
│   │   ├── ProfileSection.tsx       # Profile photo + bio + interests/education
│   │   ├── CollapsibleSection.tsx   # Reusable collapsible wrapper
│   │   └── ScrollToTop.tsx          # Floating back-to-top button
│   ├── data/
│   │   ├── journalArticles.ts       # Publication data
│   │   └── books.ts                 # Books and chapters data
│   └── App.tsx                      # Main application with all sections
```

## 🚀 Usage

### Navigation
- Click navigation items to scroll to sections
- Click section headers to expand/collapse
- Use "Back to Top" button when scrolling down

### Publications
- Switch between tabs: Journal Articles, Books, Book Chapters
- Click linked titles to view full papers
- Tags show research topics

### Reading Mode
- Expand sections you're interested in
- Collapse others to reduce scrolling
- Clean reading experience without distractions

## 🌟 Design Improvements

✅ **Minimalist navigation** - Only 4 essential items  
✅ **Collapsible sections** - Reduce clutter, improve focus  
✅ **No card borders** - Fluid, document-style layout  
✅ **Circular profile photo** - Modern academic aesthetic  
✅ **Side-by-side content** - Interests and Education in columns  
✅ **Clean typography** - Professional and readable  
✅ **Subtle dividers** - Content separation without visual noise  
✅ **Publications default open** - Most important content visible  

---

**Inspired by modern academic profile designs • Built for clarity and professionalism**

# CloudStack-Pricing

A modern and fully responsive cloud pricing section built with Tailwind CSS.  
This project focuses on utility-first styling, responsive layouts, interactive UI elements, and clean typography while maintaining a professional SaaS-inspired design system.

The interface adapts seamlessly across mobile, tablet, and desktop screens while showcasing pricing tiers in a visually balanced and scalable layout.

---

## 🚀 Live Features

- Fully responsive pricing cards
- Tailwind CSS utility-first styling
- Mobile-first design approach
- Interactive hover animations
- Featured “Most Popular” pricing tier
- Clean SaaS/cloud-inspired UI
- Professional footer section
- Accessible typography hierarchy
- Responsive grid layout
- Hidden bonus features on smaller devices
- Smooth transitions and scaling effects

---

# 🛠️ Built With

- HTML5
- Tailwind CSS (CDN Version)

---

# 📱 Responsive Design

The project uses Tailwind’s responsive utility classes to ensure a smooth experience across different screen sizes.

## Breakpoints Used

| Breakpoint | Purpose |
|---|---|
| `sm` | Small devices |
| `md` | Tablet/Desktop layout |
| `lg` | Larger screen optimization |

---

# 🎨 Design System

The project follows a modern cloud-platform aesthetic using:

- Indigo primary color palette
- Gray neutral backgrounds
- Rounded card components
- Elevated shadows and hover states
- Strong typography hierarchy
- Spacious layouts using Tailwind spacing scale

---

# 📂 Project Structure

```bash
cloudstack-pricing/
│
├── index.html
└── README.md
```

---

# ⚙️ Installation & Setup

1. Clone the repository

```bash
git clone https://github.com/your-username/cloudstack-pricing.git
```

2. Navigate into the project folder

```bash
cd cloudstack-pricing
```

3. Open the project

You can:
- Open `index.html` directly in your browser
- OR use the VS Code Live Server extension

---

# 💡 Why Grid Was Used Instead of Flexbox

CSS Grid was chosen for the pricing layout because the project contains evenly spaced pricing cards that need structured alignment across multiple screen sizes.

Grid makes it easier to:
- Maintain equal column widths
- Control spacing consistently
- Create responsive multi-column layouts
- Stack cards vertically on mobile devices

The layout transitions from:

```html
grid-cols-1
```

on mobile devices to:

```html
md:grid-cols-3
```

on larger screens.

---

# ✨ Key Tailwind Utilities Used

| Utility | Purpose |
|---|---|
| `grid` | Responsive pricing layout |
| `container mx-auto` | Centered content |
| `hover:-translate-y-2` | Lift hover animation |
| `transition-transform` | Smooth interactions |
| `ring-4` | Featured card emphasis |
| `tracking-widest` | Premium typography styling |
| `space-y-4` | Consistent spacing |
| `hidden md:block` | Responsive visibility |

---



# 🔮 Future Improvements

Potential future enhancements include:

- Dark mode toggle
- Monthly/Yearly pricing switch
- Animated pricing transitions
- Real backend subscription integration
- Improved accessibility features
- Custom Tailwind configuration

---

# 🤝 Collaboration & Contributions

Contributions, suggestions, and improvements are welcome.

To contribute:

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/your-feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to your branch

```bash
git push origin feature/your-feature-name
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# Author

Developed by Aisha Wanjiru.
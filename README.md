# Pakistani Tax Calculator 🇵🇰

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

A modern, responsive, and accurate tax calculator for Pakistani income tax calculations. Built with vanilla HTML, CSS, and JavaScript with a beautiful, user-friendly interface.

## ✨ Features

- **🎯 Accurate Tax Calculations**: Implements correct Pakistani tax slabs for multiple years
- **📱 Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **🗓️ Multi-Year Support**: Calculate taxes for years 2021-22 through 2025-26
- **💰 Flexible Input**: Support for both monthly and annual income calculations
- **📊 Detailed Results**: Shows annual tax, monthly tax, net income, and effective tax rate
- **🎨 Modern UI**: Beautiful gradient design with smooth animations
- **⚡ Real-time Calculations**: Instant results with Enter key support
- **📈 Tax Slab Display**: Visual representation of current tax brackets
- **🔄 Year Comparison**: See how tax rates have changed over the years

## 🚀 Demo

You can view the live calculator by opening the HTML file in any modern web browser.

## 📋 Tax Years Supported

| Tax Year | Status | Notes |
|----------|---------|-------|
| 2025-26 | Projected | 2% additional increase from 2024-25 |
| 2024-25 | Current | Increased burden on middle/high earners |
| 2023-24 | Historical | Moderate increases for higher income |
| 2022-23 | Historical | Progressive rate increases introduced |
| 2021-22 | Historical | Lower rates, taxpayer-friendly structure |

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/pakistani-tax-calculator.git
   cd pakistani-tax-calculator
   ```

2. **Open the calculator**
   ```bash
   # Simply open the HTML file in your browser
   open pak_tax_calculator_by_wun.html
   # or
   double-click pak_tax_calculator_by_wun.html
   ```

No build process or dependencies required! It's a single HTML file with embedded CSS and JavaScript.

## 📖 Usage

1. **Select Income Type**: Choose between Monthly or Annual income
2. **Enter Income**: Input your income amount in Pakistani Rupees (PKR)
3. **Select Tax Year**: Choose the relevant tax year for calculation
4. **Calculate**: Click "Calculate Tax" or press Enter
5. **View Results**: See detailed breakdown including:
   - Annual taxable income
   - Total tax payable
   - Monthly tax deduction
   - Net income (after tax)
   - Effective tax rate

## 💡 Tax Calculation Logic

The calculator uses Pakistan's progressive tax system where different portions of income are taxed at different rates:

### Example Tax Slabs (2024-25)
- **PKR 0 - 600,000**: 0% (Tax-free)
- **PKR 600,001 - 1,200,000**: 5%
- **PKR 1,200,001 - 2,200,000**: 15%
- **PKR 2,200,001 - 3,200,000**: 25%
- **PKR 3,200,001 - 4,100,000**: 30%
- **Above PKR 4,100,000**: 35%

## 🎨 Features Showcase

### Modern Design Elements
- **Glassmorphism Effects**: Backdrop blur and transparency
- **Gradient Backgrounds**: Beautiful blue gradient theme
- **Smooth Animations**: Hover effects and transitions
- **Responsive Layout**: Mobile-first design approach
- **Interactive Elements**: Pulse animations on tax highlights

### User Experience
- **Input Validation**: Prevents invalid entries
- **Keyboard Navigation**: Enter key support for quick calculations
- **Visual Feedback**: Loading states and smooth scrolling
- **Clear Typography**: Easy-to-read fonts and proper contrast

## 🏗️ Technical Details

### Built With
- **HTML5**: Semantic markup and modern standards
- **CSS3**: Flexbox, Grid, Custom Properties, Animations
- **Vanilla JavaScript**: No frameworks or dependencies
- **Progressive Enhancement**: Works without JavaScript for basic functionality

### Browser Support
- ✅ Chrome/Chromium (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

```css
/* Mobile First Approach */
@media (max-width: 768px) {
  /* Mobile optimizations */
}
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes**
4. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
5. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
6. **Open a Pull Request**

### Areas for Contribution
- 🔧 Additional tax years
- 🌐 Localization (Urdu support)
- 📊 Chart visualizations
- 🧮 Advanced tax scenarios
- ♿ Accessibility improvements
- 🎨 UI/UX enhancements

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This calculator is for educational and estimation purposes only. Tax calculations may vary based on individual circumstances, deductions, and current tax laws. Always consult with a qualified tax advisor or the Federal Board of Revenue (FBR) for official tax advice.

## 👨‍💻 Developer

**Waqar Un Nabi**
- Empowering financial clarity with elegant simplicity
- Creating tools that make complex calculations accessible to everyone

## 🙏 Acknowledgments

- Federal Board of Revenue (FBR) Pakistan for tax slab information
- Pakistani tax regulations and guidelines
- Modern web design principles and accessibility standards

## 🔄 Changelog

### Version 1.0.0 (Current)
- ✅ Initial release with multi-year support
- ✅ Responsive design implementation
- ✅ Accurate tax calculation engine
- ✅ Modern UI with animations

---

**Made with ❤️ for the Pakistani community**

*Helping individuals and professionals calculate their income tax with confidence and accuracy.*

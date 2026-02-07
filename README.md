# DIG Framework Analyzer

An AI-powered document analysis tool that uses Claude to break down content into **Data**, **Information**, and **Guidance** using the structured DIG framework.

## 🔗 Live Demo

[View Live Tool](https://smbrownai.github.io/dig-framework-analyzer/)

## 📋 What is the DIG Framework?

The DIG framework is a three-level analytical approach that transforms raw content into actionable insights:

- **📊 Data**: Raw facts, figures, observations, and key points extracted from the content
- **💡 Information**: Patterns, trends, insights, and meaning derived from the data
- **🎯 Guidance**: Actionable recommendations and strategic next steps based on the information

## ✨ Features

- **Multiple File Formats**: Upload PDFs, images (PNG, JPG, JPEG, WEBP, GIF)
- **AI-Powered Analysis**: Leverages Claude Sonnet 4 for intelligent content analysis
- **Structured Output**: Automatically organizes results into clear D-I-G sections
- **Custom Focus**: Optional field to direct analysis toward specific goals
- **Privacy-First**: All processing happens client-side; your API key never leaves your browser
- **Token Tracking**: See exactly how many tokens each analysis uses
- **Drag-and-Drop**: Easy file upload with visual feedback
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **No Backend Required**: Single HTML file - works offline after download

## 🚀 Getting Started

### Quick Start

1. **Get an API Key**
   - Sign up at [console.anthropic.com](https://console.anthropic.com)
   - Create a new API key in your account settings
   - Note: API usage costs money based on tokens used

2. **Use the Tool**
   - Open the HTML file in any modern browser
   - Enter your Anthropic API key
   - Upload a document
   - Click "Analyze with DIG Framework"

### Local Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/dig-framework-analyzer.git

# Open the file
cd dig-framework-analyzer
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

No build process, dependencies, or installation required!

## 📖 How to Use

### Basic Analysis

1. Enter your Anthropic API key
2. Upload a PDF or image file
3. Click "Analyze with DIG Framework"
4. Review the structured results in three sections

### Focused Analysis

For targeted insights, use the "What do you want to analyze?" field:

**Examples:**
- "Identify the main business risks and opportunities"
- "What are the key financial metrics?"
- "Summarize the research findings and methodology"
- "Extract action items and deadlines"
- "Compare the pros and cons presented"

## 💡 Use Cases

### Business
- Analyze reports, proposals, and presentations
- Extract insights from financial statements
- Review competitor analysis documents
- Evaluate business plans

### Academic
- Break down research papers
- Analyze case studies
- Review literature and articles
- Extract key findings from studies

### Personal
- Analyze contracts and legal documents
- Review medical reports
- Evaluate real estate documents
- Break down technical manuals

## 🛠️ Technical Details

- **Technology**: Pure HTML, CSS, and JavaScript
- **AI Model**: Claude Sonnet 4 (claude-sonnet-4-20250514)
- **API**: Anthropic Messages API
- **Dependencies**: None (completely self-contained)
- **Browser Support**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **File Size**: ~20KB (single file)

## 🔒 Privacy & Security

- **No data storage**: Files and analysis results are never stored
- **Client-side only**: All processing happens in your browser
- **API key security**: Stored locally in memory only, never transmitted except to Anthropic
- **No tracking**: Zero analytics or data collection
- **No server**: Direct API communication with Anthropic only

## 💰 Cost Information

This tool uses the Anthropic API, which charges based on token usage:

- **Input tokens**: Content you upload
- **Output tokens**: Analysis Claude generates

Typical costs per analysis:
- Small document (1-2 pages): $0.05 - $0.15
- Medium document (5-10 pages): $0.20 - $0.50
- Large document (20+ pages): $0.50 - $2.00

Check current pricing at [anthropic.com/pricing](https://www.anthropic.com/pricing)

## 📊 Example Output

```
DATA
• Document contains Q4 revenue of $2.3M (up 15% YoY)
• Customer acquisition cost increased to $450
• Churn rate decreased to 3.2%
• Three new product features launched

INFORMATION
• Revenue growth is strong but slowing from Q3's 22%
• CAC increase suggests marketing efficiency challenges
• Lower churn indicates improved product-market fit
• Feature velocity demonstrates engineering capacity

GUIDANCE
• Investigate marketing channel efficiency to reduce CAC
• Capitalize on low churn with expansion revenue initiatives
• Continue product development pace
• Set Q1 target of 18% revenue growth as realistic goal
```

## 🤝 Contributing

Contributions welcome! Areas for improvement:

- Support for additional file formats (DOCX, TXT)
- Batch processing multiple files
- Export results to PDF/DOCX
- Save analysis history locally
- Custom DIG framework variations
- Multi-language support

## 🐛 Troubleshooting

**"API request failed"**
- Verify your API key is correct
- Check you have API credits available
- Ensure file size is under 5MB

**"Unsupported file type"**
- Currently supports: PDF, PNG, JPG, JPEG, WEBP, GIF
- Try converting your file to PDF

**Analysis seems incomplete**
- Some files may be too complex for single analysis
- Try uploading specific pages instead of entire document
- Use the focus field to narrow the scope

## 📄 License

This project is open source and available for personal and commercial use.

## 🙏 Acknowledgments

- Built with [Claude](https://www.anthropic.com/claude) by Anthropic
- DIG framework based on established information analysis methodologies

## 📞 Support

- **Issues**: Open an issue on GitHub
- **API Questions**: Visit [Anthropic Documentation](https://docs.anthropic.com)
- **General Questions**: Check the discussions tab

---

**Made with 🤖 and the DIG Framework**

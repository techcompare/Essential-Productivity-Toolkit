# Contribution Guidelines

Thank you for considering contributing to the Essential Productivity Toolkit! This project thrives on community contributions and we welcome your input.

Please note that this project is released with a [Contributor Code of Conduct](https://github.com/sindresorhus/.github/blob/main/code-of-conduct.md). By participating in this project you agree to abide by its terms.

---

## 🎯 What We're Looking For

We welcome contributions that:
- **Add valuable productivity tools** that genuinely improve workflow
- **Enhance existing content** with better descriptions or organization
- **Fix errors** including typos, broken links, or outdated information
- **Improve documentation** making resources easier to navigate
- **Share personal experiences** with tools (in discussions)

---

## 📋 Quality Criteria

Before suggesting a tool, please ensure it meets these criteria:

### Essential Requirements
- ✅ **Legitimacy** - From reputable developers/companies
- ✅ **Safety** - No malware, adware, or security concerns
- ✅ **Functionality** - Actually works and solves a problem
- ✅ **Accessibility** - Available to users (not discontinued)
- ✅ **Official Source** - Link goes to official website/repository

### Preferred Characteristics
- 🌟 **Free or Free Tier** - Accessible to everyone
- 🔓 **Open Source** - Transparency and community-driven
- 🔒 **Privacy-Respecting** - Doesn't exploit user data
- 🌍 **Cross-Platform** - Works on multiple operating systems
- 📱 **Mobile-Friendly** - Has mobile apps or responsive web interface
- 🔄 **Actively Maintained** - Regular updates and support

---

## 🚀 How to Contribute

### Method 1: Quick Suggestion (Issues)

**Best for:** Single tool suggestions or simple fixes

1. Go to [Issues](https://github.com/techcompare/Essential-Productivity-Toolkit/issues)
2. Click "New Issue"
3. Use this template:

```markdown
**Tool Name:** [Name of Tool]
**Category:** [Which file should it be added to?]
**Link:** [Official website URL]
**Description:** [Brief description of what it does]
**Why it's great:** [What makes this tool valuable?]

**Additional Context:**
- Free/Paid: 
- Platform(s):
- Open Source: Yes/No
```

### Method 2: Pull Request

**Best for:** Multiple additions, new sections, or significant improvements

1. **Fork** the repository
2. **Create a branch** (`git checkout -b add-new-tool`)
3. **Make your changes** following the format guidelines below
4. **Test your changes** (check links, spelling, formatting)
5. **Commit** (`git commit -m 'Add [Tool Name] to [Category]'`)
6. **Push** (`git push origin add-new-tool`)
7. **Open a Pull Request** with a clear description

---

## 📝 Format Guidelines

### Adding a New Tool

Follow this exact format:

```markdown
- [Tool Name](https://official-website.com) - Clear, concise description in sentence case explaining what it does and why it's useful.
```

**Format Rules:**
- Use title case for tool names
- Start description with capital letter
- End description with period
- Keep descriptions under 150 characters when possible
- Focus on what it does, not marketing fluff
- Include key differentiators (free, open-source, etc.)

**Good Examples:**
```markdown
- [Notion](https://www.notion.so) - All-in-one workspace combining notes, databases, and project management.
- [Bitwarden](https://bitwarden.com) - Open-source password manager with cloud sync or self-hosting option.
- [uBlock Origin](https://ublockorigin.com) - Efficient ad blocker and content filter.
```

**Bad Examples:**
```markdown
- [Tool] (http://website.com) - description
- [AWESOME TOOL!!!](link) - The best tool ever made!!! You must try this!!!
- [Tool](link) Revolutionary AI-powered next-generation platform...
```

### File Organization

#### Within Existing Files
- Add tools to the **bottom** of the relevant section
- If suggesting a new section, explain why it's needed
- Keep alphabetical order where it exists

#### Category Subcategories
When a category has subcategories (like in new files):
```markdown
## Main Category

Brief introduction to this category.

### Subcategory Name

- [Tool 1](link) - Description.
- [Tool 2](link) - Description.

### Another Subcategory

- [Tool 3](link) - Description.
```

---

## 🔍 Verification Checklist

Before submitting, verify:

- [ ] Tool link goes to **official website** (not third-party review sites)
- [ ] Description is **clear and concise**
- [ ] Spelling and **grammar are correct**
- [ ] Follows the **exact format** specified above
- [ ] Tool is in the **right category**
- [ ] No **duplicate entries** (search before adding)
- [ ] Link is **working** (test it!)
- [ ] Tool is **actively maintained** (not abandoned)
- [ ] Appropriate for **productivity focus** of this repository

---

## 🎨 Style Guide

### Writing Style
- **Clear and Direct** - Get to the point quickly
- **Neutral Tone** - Avoid hype or exaggeration
- **Consistent Voice** - Match existing descriptions
- **Action-Oriented** - Focus on what users can do

### Avoid
- ❌ Marketing speak ("revolutionary," "game-changing," "best ever")
- ❌ Affiliate links or referral codes
- ❌ Self-promotion without value
- ❌ Excessive punctuation or emoji in descriptions
- ❌ Subjective opinions without context
- ❌ Incomplete or vague descriptions

### Prefer
- ✅ Factual, specific information
- ✅ Key features and use cases
- ✅ Platform availability
- ✅ Free/paid status
- ✅ Open-source designation
- ✅ Privacy-focused callouts

---

## 🔗 Link Guidelines

### Link Requirements
1. **Always use HTTPS** when available
2. **Link to official sources only**
   - Main website
   - Official GitHub repository
   - Official download page
3. **Avoid:**
   - Shortened URLs (bit.ly, tinyurl)
   - Affiliate or referral links
   - Third-party download sites
   - Review or comparison sites
   - Your own blog or YouTube channel (unless you're the official developer)

### Valid Link Examples
- `https://www.notion.so` (Official website)
- `https://github.com/bitwarden` (Official GitHub)
- `https://obsidian.md` (Official domain)

### Invalid Link Examples
- `http://bit.ly/tool123` (Shortened URL)
- `https://example.com/tools/review` (Third-party review)
- `https://softonic.com/download` (Third-party download)
- `https://yoursite.com?ref=123` (Referral link)

---

## 🆕 Adding New Categories

Before suggesting a new category file:

1. **Check if it fits** in existing categories
2. **Ensure sufficient content** (20+ quality tools minimum)
3. **Provide clear rationale** for why it's needed
4. **Follow existing file structure**

New category template:
```markdown
# Category Name

Brief introduction explaining what this category covers.

Why this category matters for productivity.

## Subcategory 1

- [Tool](link) - Description.
- [Tool](link) - Description.

## Subcategory 2

- [Tool](link) - Description.
```

---

## 🐛 Reporting Issues

### Broken Links
Report with:
- Which file
- Which tool
- What the issue is
- Suggested fix (if known)

### Outdated Information
Report with:
- What's outdated
- Correct current information
- Source for the update

### Errors or Typos
- Clearly indicate the mistake
- Provide the correction
- Small fixes can be PR'd directly

---

## 💬 Discussions vs Issues vs PRs

### Use Discussions for:
- General questions
- Tool recommendations
- Sharing productivity tips
- Feature ideas
- Community conversation

### Use Issues for:
- Bug reports
- Broken links
- Specific tool suggestions
- Content errors
- Missing information

### Use Pull Requests for:
- Adding new tools
- Fixing errors
- Improving documentation
- Reorganizing content
- Adding new sections

---

## ⏱️ Response Time

- **Simple PRs** - Reviewed within 1-3 days
- **Complex PRs** - Reviewed within 1 week
- **Issues** - Acknowledged within 3-5 days
- **Discussions** - Community-driven, no set timeline

We appreciate your patience! This is a community-driven project.

---

## 🎯 Priority Areas

We're especially interested in contributions for:

1. **AI Productivity Tools** - Emerging AI applications
2. **Privacy-Focused Alternatives** - FMHY-style resources
3. **Open Source Projects** - Community-driven tools
4. **Free Alternatives** - Accessible to everyone
5. **Mobile Productivity** - iOS and Android apps
6. **Developer Tools** - Coding and development resources
7. **Content Creation** - Media and creative tools

---

## 🚫 What We Don't Accept

- **Piracy or illegal content** - Only legitimate software
- **Malware or suspicious software** - Must be safe
- **Paid-only with no free tier** - Prefer free or freemium
- **Abandoned projects** - Must be actively maintained
- **Self-promotion without value** - Must genuinely help users
- **Duplicate submissions** - Check existing tools first
- **Off-topic content** - Must relate to productivity
- **Spam or low-effort submissions** - Quality over quantity

---

## 📚 Resources for Contributors

- [Markdown Guide](https://www.markdownguide.org/) - Learn markdown syntax
- [GitHub Docs](https://docs.github.com/) - How to use GitHub
- [Conventional Commits](https://www.conventionalcommits.org/) - Commit message format
- [Open Source Guide](https://opensource.guide/) - Contributing to open source

---

## 🏆 Recognition

Contributors are recognized in:
- Git commit history
- Pull request acknowledgments
- Community discussions
- Project supporters list

Every contribution, no matter how small, is valued!

---

## 📧 Questions?

- **General Questions** - Use [Discussions](https://github.com/techcompare/Essential-Productivity-Toolkit/discussions)
- **Specific Issues** - Open an [Issue](https://github.com/techcompare/Essential-Productivity-Toolkit/issues)
- **Sensitive Matters** - Contact repository maintainers

---

## 🙏 Thank You

Thank you for taking the time to contribute! Your efforts help thousands of people discover tools that improve their productivity and workflow.

**Happy Contributing!** 🎉

---

<div align="center">

**[⬆ Back to Top](#contribution-guidelines)**

</div>



# Analysis of Documentation Platform Selection for the RaKo ICT Knowledge Base

## 1. Introduction

This report is part of the *Information Security Management* module in the ICT Security Specialist curriculum at Rapla County Applied College (RaKo).  
The objective of the assignment is to design, implement, and justify a personal study knowledge base that will serve as an ongoing portfolio throughout the curriculum.

In addition to creating the knowledge base, the task requires performing a comparative analysis between different documentation platforms and explaining the reasoning behind the chosen solution.

## 2. Assignment Description

The assignment consists of the following components:

- Create a structured, long-term knowledge base for documenting study progress.
- Choose an appropriate platform for hosting this knowledge base.
- Compare the chosen solution with at least three alternative platforms.
- Analyze the platform from a security management perspective.
- Provide a clear justification for why this specific platform was selected.

I implemented my knowledge base using **GitHub Pages** combined with Markdown documentation inside a public GitHub repository.

## 3. Overview of the Chosen Platform: GitHub

GitHub is a widely used platform for software development, documentation, and version control.  
My solution uses:

- **GitHub Repository** → stores Markdown files, images, folders, and structure  
- **GitHub Pages** → publishes documentation as a clean website  
- **Just the Docs theme** → provides navigation, sidebar, and search  
- **Markdown** → simple and universal documentation format  

### Key benefits:

- Free to use  
- Supports Markdown, images, downloadable files  
- Integrates code repositories and documentation in one ecosystem  
- Includes a built-in Wiki feature  
- Easy to share publicly (portfolio link)  
- Strong version control (Git)  
- Good for long-term maintenance  
- Teaches real industry skills  

## 4. Comparison With Alternative Platforms

The following alternatives were considered:

- **Atlassian Confluence**  
- **Notion**  
- **MediaWiki (self-hosted)**  

### Comparison Table

| Feature | **GitHub Pages** | **Confluence** | **Notion** | **MediaWiki (self-hosted)** |
|--------|-------------------|----------------|------------|------------------------------|
| Cost | Free | Paid | Free + Paid | Free, hosting required |
| Ease of Setup | Easy | Medium | Very easy | Complex |
| Markdown Support | Yes | Limited | Yes | Yes |
| Code Integration | Excellent | Poor | Weak | Medium |
| Public Sharing | Excellent | Limited | Good | Depends on hosting |
| Security | GitHub-managed | Enterprise-grade | Vendor-managed | User-managed |
| Maintenance | Very low | Low–medium | Low | Very high |
| Best Use Case | Students/Developers/Portfolios | Corporate teams | Personal notes | Community wikis |

## 5. Security Analysis

Because this analysis belongs to the *Information Security Management* module, the platform was reviewed from a security perspective.

### 5.1 GitHub Security Strengths

- Professionally maintained and hardened infrastructure  
- Automatic security updates, patching, backups  
- Distributed global CDN  
- 2FA, SSH authentication, private repositories  
- Strong auditability through Git commit history  
- No server management required (reduces operational risk)

### 5.2 Confluence Security Considerations

- Cloud version stores data in Atlassian’s environment  
- Server version requires manual patching, monitoring, backups  
- Designed for enterprise use, not personal or educational portfolios  

### 5.3 Notion Security Considerations

- Hosted SaaS platform  
- No Git-style revision control  
- Not optimized for technical documentation  
- Limited control over data location  

### 5.4 Self-Hosted MediaWiki Security Considerations

- Requires managing the entire server stack (web server, OS, database)  
- Manual patching and vulnerability management  
- High risk of misconfiguration  
- Not ideal for a student project or personal portfolio  

## 6. Justification for Choosing GitHub

GitHub was selected because it provides:

- A free, secure, and low-maintenance environment  
- Easy integration of Markdown, images, files, and code  
- Built-in Wiki support  
- Publicly accessible documentation suitable for a professional portfolio  
- Strong version control and collaboration features  
- A clean, navigable website using GitHub Pages  
- Bilingual documentation support  
- Minimal security overhead compared to self-hosting  

For an ICT Security Specialist student, GitHub also offers practical experience with industry-standard tools such as Git, documentation workflows, and repository management.

## 7. Conclusion

GitHub provides the best balance of usability, security, flexibility, and professional value among the compared platforms.  
It supports all requirements of the assignment while also serving as a long-term portfolio tool that can be shared with instructors and future employers.

For these reasons, GitHub was the most reasonable and secure choice for creating my RaKo ICT Knowledge Base.

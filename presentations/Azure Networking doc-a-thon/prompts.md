# AI-Enhanced Documentation with GitHub Copilot
# Author: Michael Bender - Senior Content Developer, Microsoft
# Presentation Date: 07/08/2024

This guide provides practical prompts and workflows for using GitHub Copilot to enhance technical documentation processes. These examples demonstrate how AI assistance can streamline common documentation tasks including content creation, analysis, and quality improvement.

The prompts in this collection are designed to help technical writers:

Create comprehensive documentation that follows Microsoft Style Guide standards
Analyze existing content for gaps, outdated information, and compliance issues
Generate specialized content types like best practices guides and FAQs
Perform quality assurance through automated fact-checking and validation
Each section includes specific prompt examples with context about the intended workflow. These prompts emphasize adherence to Microsoft documentation standards, SEO optimization, and fact-checking against authoritative sources.
## Github Coplilot Chat

### Ask mode

**Prompt:**
```vscode
How would I convert this article to use Azure CLI vs. PowerShell
```

### Edit mode

**Prompts:**

```vscode
List all of the tools currently available in Agent mode.
If a tool is available due to a VS Code extension, please call out the extension name
```

```vscode
Convert PowerShell to Azure CLI and modify all references to Azure CLI
```

### Agent mode

**Prompt:**
```vscode
Convert this article to use Azure CLI.
Update all references to PowerShell.
Verify that all commands used are actual commands from Microsoft documentation.
```

## Documentor

Help with extensions /help

Review the Documentor extension for GitHub Copilot

### Convert Word to Markdown

Right-Click > Documentor > ...
> Show Encryption error
> Change doc to General
> Review Converted doc
> Add Metadata
> Auto fix Markdown & review prompt

```vscode
Convert all PowerShell code to use PowerShell code blocks
```

```vscode
Add ##Next Steps section at bottom with an article related to network security perimeter using powershell
```

TOC updates

### Documentor options


## MCP Server

## Demo - Create a best practices document for AVNM

**Prompt:**

```vscode
Based Microsoft Learn Documentation, create a best practices document for Azure Virtual Network Manager.

- Check against TechCommunity.com blogs as well as other public facing microsoft docs.
- Ensure it covers architecture, deployment, security, and management/monitoring.
- Add to a document called avnm-best-practices.md in the current folder.
Optimize the document for SEO and Generative Engine optimization. Adhere to the Microsoft Style Guide.
- Follow examples of other best practices in Microsoft docs for examples.

When the document is complete, fact-check all the items against current documention set. Identify corrections and provide links/urls to references for corrections.
```

## Demo - Analysis of articles

**Scenario:**

```vscode
Ask Copilot to list the number of articles in a service's folder, How many articles are older than 365 days, and how many article are missing customer intent statements in metadata.
```

**Prompt:**

```vscode
- How many markdown articles are in the load-balancer folder?
- How many have ms.dates older than 07/03/2024?
- How many are missing # customer intent:" statements?
```

## Demo - create an FAQ article for Load Balancer

**Prompt:**

```vscode
Utilizing Microsoft Learn documentation and all public Microsoft documentation, create an FAQ for Troubleshooting Azure Load Balancer.
Create FAQ.yml in the current folder.
Follow microsoft style guide and best practices for FAQ documentation.
Optimize the FAQ for Generative Engine Optimization.
```

**Prompt2:**

```vscode
Fact check FAQ.yml results against our current documentation set. Identify any items that don't align in the new FAQ.
```

## Demo - Gap Analysis

**Prompt:**
```vscode
Based on a review of customer-facing Microsoft official documentation and blogs on tech community, analyze the virtual network manager doc set for scenarios and article gaps missing in our public documentation.

Create a new file including all the Article gaps, a high-level summary of what a new doc would include. Create article in current folder with name avnm-gap-analysis.md

include all links and references to fact-check recommendations.
```


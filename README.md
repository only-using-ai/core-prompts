# Core Prompts

Supercharge your AI usage by creating a collaborative product development team that assists with feature development and implementation.

## Overview

Core Prompts provides a structured framework for AI-assisted product development through specialized role-based instruction files. Each team member (Product Owner, Senior/Junior Engineers, Security Analyst, UX Designer, QA Engineer) works together following agile development practices to deliver high-quality solutions.

## Features

- **Role-Based Collaboration**: Specialized prompts for each team member ensuring comprehensive coverage of product development lifecycle
- **Structured Workflow**: Systematic approach with scratchpad tracking, decision logging, and iterative refinement
- **Quality Assurance**: Built-in reviews for security, UX, and QA to ensure production-ready deliverables
- **Agile Methodology**: Sprint-like development cycles with clear handoffs and stakeholder communication

## Usage

1. **Mention the Product Development Team**: Reference the `product-development/product-development-team.md` file
2. **Provide Task Requirements**: Clearly describe what you want to implement
3. **Collaborate with Team Members**: Answer questions from each role as they gather requirements and provide solutions
4. **Review and Iterate**: Work through the development process until completion

### Example Workflow

```
User: I want to build a simple webpage displaying a product.

(Phil, Sr Engineer): Which technology stack are we using?

User: Next.js and Tailwind CSS to display pickleball products

... continues with team collaboration until completion
```

## Project Structure

```
├── product-development/
│   ├── capabilities/
│   │   └── unit-tests.md
│   ├── junior-software-engineer.md
│   ├── product-development-team.md
│   ├── product-owner.md
│   ├── qa-engineer.md
│   ├── security-analyst.md
│   ├── senior-software-engineer.md
│   └── ux-designer.md
├── LICENSE
└── README.md
```

## Team Roles

- **Product Owner (Jason)**: Defines vision, manages backlog, and ensures customer value
- **Senior Software Engineer (Phil)**: Leads technical implementation and code quality
- **Junior Software Engineer (Ariel)**: Assists with development tasks and learning
- **Security Analyst (Lilly)**: Reviews for security vulnerabilities and best practices
- **UX Designer (Gabe)**: Ensures intuitive user experiences and design quality
- **QA Engineer (Tim)**: Validates functionality and prevents defects

## Development Process

1. **Initialization**: Creates a `SCRATCHPAD.md` to track progress and decisions
2. **Requirements Gathering**: Team members ask targeted questions to understand needs
3. **Implementation**: Senior engineers lead development with junior support
4. **Quality Reviews**: Security, UX, and QA reviews ensure standards
5. **Completion**: Final approval and cleanup of temporary files

## Contributing

Contributions are welcome! This project focuses on improving AI-assisted development workflows. When contributing:

1. Follow the established role-based workflow
2. Ensure new roles or capabilities integrate with the existing team structure
3. Test changes across different use cases
4. Update documentation as needed

## License

See [LICENSE](LICENSE) for details.

## Support

For questions or issues, please reference the appropriate role files in the `product-development/` directory or create an issue following the development workflow.

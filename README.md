# Experiment Name

## Overview

Brief description of what this experiment aims to accomplish.

## Goals

1. Primary goal
2. Secondary goal
3. Tertiary goal

## Success Criteria

- [ ] Measurable outcome 1
- [ ] Measurable outcome 2
- [ ] Measurable outcome 3

## Status

**Current Stage:** Scoped
**Owner:** [Your Name]
**Started:** [Date]
**Last Updated:** [Date]

## Development

### Prerequisites

- Node.js (version specified in `.nvmrc` or package.json engines)
- HubSpot `bend` CLI tools
- TypeScript knowledge

### Setup

```bash
# Install dependencies
npm install

# Or if using HubSpot's package manager
hs-package-manager install
```

### Running

```bash
# Start development server with hot reload
bend reactor serve --enable-tools --ts-watch

# For development with tests running
bend reactor serve --enable-tools --ts-watch --run-tests
```

### Type Checking

```bash
# Type check will happen automatically in watch mode
# Or check manually (requires bend process running)
# Use mcp__devex-mcp-server__bend_package_ts_get_errors tool
```

### Linting

```bash
# Run ESLint
bend hs-eslint
```

### Testing

```bash
# Tests run automatically when using --run-tests flag
# Or check test results (requires bend process running)
# Use mcp__devex-mcp-server__bend_package_get_tests_results tool
```

### Building

```bash
# Compile the project (requires bend process running)
# Use mcp__devex-mcp-server__bend_compile tool
```

## Architecture

Brief description of technical approach and key technologies used:
- React + TypeScript
- HubSpot `bend` build system
- Testing with Jasmine and React Testing Library

## Resources

- [DevRel Labs Meta Repo](https://github.com/your-org/DevRel-Labs-Meta-Repo)
- [Experiment Proposal Issue](#)
- [HubSpot Frontend Documentation](https://product.hubteam.com/docs/frontend/)
- [Bend Reactor Documentation](https://product.hubteam.com/docs/frontend/docs/bend.html)

## Contributing

This is a DevRel Labs experiment. See the [main meta repo](https://github.com/your-org/DevRel-Labs-Meta-Repo) for participation guidelines.

## Questions?

- **Slack:** #devrel-labs
- **Owner:** @your-username

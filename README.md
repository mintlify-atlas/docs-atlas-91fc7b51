# OpenJDK Documentation

This repository contains the documentation for the OpenJDK project, the open-source reference implementation of the Java Platform, Standard Edition.

## Documentation Structure

- **Get Started** - Introduction and quick start guide
- **Building the JDK** - Complete guide to building OpenJDK from source
- **Architecture** - Deep dive into HotSpot VM, GC, JIT compiler, and module system
- **Development** - Contributing, code style, testing, and debugging guides
- **Tools & Utilities** - Documentation for javac, jlink, jpackage, jcmd, and more
- **API Reference** - Core APIs, Desktop APIs, Networking, Security, and JVM Internals

## Local Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview the documentation locally:

```bash
npm i -g mint
```

Run the following command at the root of your documentation:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing Changes

Changes are deployed to production automatically after pushing to the default branch.

## Resources

- [OpenJDK Project](https://openjdk.org/)
- [OpenJDK Source Repository](https://github.com/openjdk/jdk)
- [Mintlify Documentation](https://mintlify.com/docs)

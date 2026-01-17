# Software Engineering Resources

A curated collection of articles, books, talks, and concepts that have shaped my approach to building software systems. These resources emphasize thoughtful architecture, pragmatic testing, and sustainable development practices.

-----

## 🏗️ Architecture & Design

### [Hexagonal Architecture](https://alistair.cockburn.us/hexagonal-architecture/)

Also known as Ports and Adapters, this pattern helps isolate business logic from external dependencies, making systems easier to test and modify.

### [Bounded Contexts](https://martinfowler.com/bliki/BoundedContext.html)

A Domain-Driven Design concept for managing complexity by establishing clear boundaries between different parts of a system.

### [High Cohesion, Loose Coupling](https://enterprisecraftsmanship.com/posts/cohesion-coupling-difference/)

Core principles for building modular systems where components have clear responsibilities and minimal dependencies.

### [The Repository Pattern](https://martinfowler.com/eaaCatalog/repository.html)

Mediates between the domain and data mapping layers, providing a collection-like interface for accessing domain objects.

### [Active Record: How We Got Persistence Perfectly Wrong](https://www.mehdi-khalili.com/orm-anti-patterns-part-1-active-record)

Critical examination of the Active Record pattern and its impact on application architecture.

-----

## 🧪 Testing

### [The Practical Test Pyramid](https://martinfowler.com/articles/practical-test-pyramid.html)

A guide to balancing unit, integration, and end-to-end tests for effective test coverage without excessive maintenance burden.

### [What is a Unit Test?](https://www.artima.com/weblogs/viewpost.jsp?thread=126923)

Explores different perspectives on what constitutes a unit test and when to use different testing approaches.

### [What is an Integration Test?](https://martinfowler.com/bliki/IntegrationTest.html)

Clarifies the purpose and scope of integration testing in modern software development.

### [Mocking at Architectural Boundaries](https://blog.cleancoder.com/uncle-bob/2014/05/10/WhenToMock.html)

Guidance on when and where to use mocks effectively without creating brittle tests.

### [When to Mock](https://blog.cleancoder.com/uncle-bob/2014/05/10/WhenToMock.html)

Practical advice on choosing between real implementations and mocks in tests.

### [Mocks aren’t Stubs](https://martinfowler.com/articles/mocksArentStubs.html)

Martin Fowler’s classic article explaining the difference between mocks, stubs, and other test doubles.

### [Avoid In-Memory Databases for Tests](https://blog.jooq.org/dont-use-in-memory-databases-for-tests/)

Why test environments should match production databases to catch real-world issues.

### [Avoid Test Duplication](https://kentcdodds.com/blog/avoid-test-duplication)

Strategies for maintaining DRY principles in test code without sacrificing clarity.

### [Why I Manage Test Fixtures Differently](https://thoughtbot.com/blog/factories-should-be-the-bare-minimum)

Alternative approaches to test data management that improve test maintainability.

-----

## 💡 Development Philosophy

### [Software as a Liability](https://www.stevestreeting.com/2020/02/04/software-as-a-liability/)

Every line of code is a maintenance burden. Write less code, solve more problems.

### [Why Assumptions are the Bane of Software Development](https://www.softwaremeadows.com/posts/the_assumptions_that_kill_software_projects/)

How unstated assumptions lead to project failures and communication breakdowns.

### [Migrations: The Sole Scalable Fix to Tech Debt](https://lethain.com/migrations/)

Strategic approach to modernizing legacy systems through deliberate, incremental migrations.

### [Building High-Quality Software](https://www.codewithjason.com/building-high-quality-software/)

Practical strategies for maintaining code quality in real-world development environments.

### [Hyrum’s Law (The Law of Implicit Interfaces)](https://www.hyrumslaw.com/)

“With a sufficient number of users, all observable behaviors of your system will be depended on by somebody.”

### [That’s Not Yours](https://8thlight.com/insights/thats-not-yours)

Understanding ownership and responsibility boundaries in object-oriented systems.

-----

## 🔧 Validation & Security

### [Where Does My Validation Live?](https://www.thoughtworks.com/insights/blog/domain-validation)

Guidance on placing validation logic at the right architectural layer.

### [Form, Command, and Model Validation](https://enterprisecraftsmanship.com/posts/validation-in-domain-driven-design-ddd/)

Different types of validation and where they belong in your architecture.

### [Sanitize Your Inputs?](https://benhoyt.com/writings/dont-sanitize-do-escape/)

Why escaping output is more effective than sanitizing input for preventing injection attacks.

-----

## 🛠️ Practical Skills

### [Learning to Build: The 5 Bedrock Skills of Innovators](https://review.firstround.com/learning-to-build-the-5-bedrock-skills-of-innovators-and-entrepreneurs)

Core competencies for engineers who want to build products, not just features.

### [Shape Up: Project Management](https://basecamp.com/shapeup)

Basecamp’s approach to product development with fixed time, variable scope.

### [How to Estimate Project Length](https://jacobian.org/2021/may/20/estimation/)

Practical techniques for making realistic project estimates.

### [Zero Downtime Database Migrations](https://fly.io/ruby-dispatch/zero-downtime-deployments/)

Strategies for safely deploying database changes in production systems.

### [Socratic Method: Fostering Critical Thinking](https://fs.blog/socratic-method/)

Using questions to drive deeper understanding and better solutions.

-----

## 📝 Code Quality

### [Interface Naming Conventions](https://blog.ploeh.dk/2021/04/19/consider-including-identity-in-urls/)

Thoughtful approaches to naming interfaces and abstractions.

### [Safer Bash Scripts](https://vaneyckt.io/posts/safer_bash_scripts_with_set_euxo_pipefail/)

Essential practices for writing reliable shell scripts with proper error handling.

### [Minimal Bash Script Template](https://betterdev.blog/minimal-safe-bash-script-template/)

A starting point for writing maintainable bash scripts.

### [Avoid the Test User](https://www.luu.io/posts/avoid-the-test-user)

Why shared test accounts create problems and how to structure tests properly.

-----

## 🎯 Why These Resources?

These articles represent principles I’ve found most valuable in real-world software development:

1. **Architecture matters** - Well-structured systems are easier to change
1. **Test strategically** - Not all tests provide equal value
1. **Code is a liability** - Every line written requires maintenance
1. **Validate thoughtfully** - Put validation logic where it belongs
1. **Migrate deliberately** - Legacy systems need strategic modernization

-----

## 📫 Discussion

Found these helpful? Have resources to suggest? Feel free to [open an issue](https://github.com/pmerrill/learning-resources/issues) or reach out on [LinkedIn](https://linkedin.com/in/petermerrill).

-----

*Last updated: January 2026*

<img src="../../assets/doc-images/edupunk-os-contributing@2x.png" srcset="../../assets/doc-images/edupunk-os-contributing@1x.png 1x, ../../assets/doc-images/edupunk-os-contributing@2x.png 2x" alt="Edupunk Contributing Mosh Pit Cover">

---

> _**[@KHTHONDEV:](https://github.com/khthondev)** This page is under developement. You can go and check **[EDUPUNK OS MANIFESTO](../main/MANIFESTO.md)**_

---

## EDUPUNK OS CONTRIBUTION GUIDELINES

### CORE VALUES FOR TECH CONTRIBUTORS

<img src="../../assets/doc-gifs/old-school-mosh.gif" width="350" alt="Old School Mosh">

---

#### 1. PRIVACY AS DEFAULT

- Start every design with privacy as the foundation, not an afterthought
- Question every data collection point: "Is this essential, and does it stay under user control?"
- Default to local storage over cloud, encryption over plaintext, minimal data over comprehensive collection
- Remember: Students and teachers should never worry about being surveilled

#### 2. SIMPLICITY OVER COMPLEXITY

- Choose the simplest viable solution for any problem
- Value readable code that future contributors can understand and modify
- Avoid dependencies unless absolutely necessary
- Single-binary deployment should remain possible
- If you can't explain your solution to a non-technical teacher, it's too complex

#### 3. RESOURCE CONSERVATION

- Every line of code should respect the constraints of decade-old hardware
- Measure and optimize memory usage, startup time, and response time
- Prefer efficient algorithms that scale well with limited resources
- Remember the teacher using a hand-me-down laptop with 4GB RAM

#### 4. TEACHER AUTONOMY

- Design interfaces and features that empower teachers to make decisions
- Avoid "opinionated" solutions that force specific workflows
- Make customization accessible through clear interfaces, not config files
- The teacher should control the software, never the reverse

#### 5. ACCESSIBILITY BY DESIGN

- Build interfaces that work for users of all abilities
- Ensure screen reader compatibility and keyboard navigation
- Support high-contrast modes and resizable text
- Test on various devices and screen sizes

#### 6. CODE AS EDUCATION

- Write code that teaches, not just functions
- Document the "why" behind decisions, not just the "how"
- View every pull request as a chance to mentor new contributors
- Structure repositories and documentation for learning, not just reference

#### 7. OFFLINE-FIRST THINKING

- Design every feature to work without internet connection
- Add synchronization as a layer on top of local functionality
- Test in environments with no connectivity, not just poor connectivity
- Remember the classroom where Wi-Fi is unreliable or non-existent

#### 8. COMMUNITY-MINDED DEVELOPMENT

- Write for future maintainers, not just for yourself
- Share knowledge openly through documentation and discussions
- Value diverse perspectives in design decisions
- Support new contributors with patience and mentorship

#### 9. ETHICAL DESIGN

- Question features that encourage addictive usage patterns
- Avoid gamification elements that prioritize engagement over learning
- Design to reduce stress, not increase it
- Consider the psychological impact of interfaces on students

#### 10. SUSTAINABLE DEVELOPMENT

- Build features that remain maintainable long-term
- Document architectural decisions for future contributors
- Create tests that verify core functionality
- Remember that education software should last for years, not months

---

## PRACTICAL APPLICATIONS

<img src="../../assets/doc-gifs/electric-enlightment.gif" width="350" alt="Electic Enlightment">

---

### FOR DESIGNERS

- Begin with user flows that respect offline scenarios
- Create wireframes that work on small screens and old browsers
- Design progressive enhancement strategies for varied capabilities
- Document design systems that other contributors can follow
- Test designs with actual teachers and students

### FOR DEVELOPERS

- Write modular code with clear interfaces
- Keep functions focused and testable
- Use performance profiling to identify bottlenecks
- Implement data minimization and expiration policies
- Prioritize backward compatibility

### FOR TECH WRITERS

- Create documentation that explains concepts, not just steps
- Develop guides for various technical levels
- Document architecture decisions and their rationales
- Create templates to encourage consistent documentation
- Build educational examples that showcase best practices

### FOR QA ENGINEERS

- Test on minimum spec hardware, not just your development machine
- Verify functionality without internet connection
- Create realistic classroom testing scenarios
- Validate privacy assumptions with data flow mapping
- Develop accessibility testing protocols

---

## CODE REVIEW CHECKLIST

<img src="../../assets/doc-gifs/old-school-mosh.gif" width="350" alt="Checklist">

---

When reviewing contributions, ensure they:

- [X] Maintain or improve privacy guarantees
- [X] Run efficiently on target minimum hardware
- [X] Work completely offline with clear sync strategy
- [X] Respect and enhance teacher autonomy
- [X] Include appropriate documentation and tests
- [X] Follow accessibility guidelines
- [X] Maintain simplicity and readability
- [X] Avoid unnecessary dependencies
- [X] Consider education contexts in design decisions
- [X] Align with our ethical principles

These principles provide a foundation for building technology that serves education rather than surveilling it, empowers teachers rather than restricting them, and respects the constraints of real classrooms rather than assuming ideal conditions.

---

<img src="../../assets/doc-images/edupunk-os-hand-eye-logo.gif" width="200px">

**THIS ISN'T JUST SOFTWARE. THIS IS EDUCATION RECLAIMED. THIS IS EDUPUNK OS**

**[github.com/khthondev/edupunk-os](https://github.com/khthondev/edupunk-os)**

> fork it / share it / make it better / guide to learn / learn to see >>>
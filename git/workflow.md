### **Simple Git Workflow**

1. **Start Project** > Begin working on a new project.
2. **Initialize Repo** > Create a new Git repository to track your code.
3. **Create Branch** > Make a separate branch to work on new features or fixes.
4. **Make Changes** > Write or edit code in your branch.
5. **Commit Changes** > Save your changes with a meaningful message.
6. **Push to Remote** > Upload your branch to a remote Git repository.
7. **Open Pull Request** > Request to merge your changes into the main branch.
8. **Code Review** > Teammates review your code for quality and correctness.
9. **Merge to Main** > After approval, merge your branch into the main codebase.

---

```mermaid
flowchart TD
    A[Start Project] --> B[Initialize Repo]
    B --> C[Create Branch]
    C --> D[Make Changes]
    D --> E[Commit Changes]
    E --> F[Push to Remote]
    F --> G[Open Pull Request]
    G --> H[Code Review]
    H --> I[Merge to Main]
    I --> J[Done ✅]

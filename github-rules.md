## Flygency Development Guidelines

Welcome to the Flygency codebase! Here, we outline our branching, merging, and overall code management guidelines. Follow these steps to ensure a smooth and efficient development process. Let's revolutionize the travel industry together!

# Branching

We use a feature branching workflow. You should create a new branch for every task or bug fix.

### To create a new branch:

1. Checkout the **development** branch:

```
git checkout development
```

2. Pull the latest changes:

```
git pull origin development
```

3. Create a new branch. Follow the naming convention **feature/feature-name-yourname** for features or **bugfix/bug-name-yourname** for bug fixes:

```
git checkout -b feature/feature-name-yourname
```

3. Create a new commit. Follow the naming convention **DONE: Issue:#10, Customer list done** on another line **TODO: Teams list pending todo**:


```
DONE: Issue:#10, Customer list done
TODO: Teams list pending todo
```

Remember to regularly merge the **development** branch into your feature branch to prevent major conflicts at the end.

# Merging

Once you've finished working on a feature, you should merge your changes into the **development** branch. Before doing so, ensure your code adheres to our style guide and passes all tests.

**Here's how to merge your feature branch into the `development` branch:**

1. Checkout the **`development`** branch:

```
git checkout development
```

2. Pull the latest changes:

```
git pull origin development
```

3. Merge your feature branch into **`development`**:

```
git merge feature/your-feature-branch
```

4. Push your changes:

```
git push origin development
```

You should also open a pull request to review your code before merging into the **development** branch.

# Pull Requests

Pull requests allow the team to review and discuss your changes before they are integrated into the main codebase. When you open a pull request, include a brief summary of your changes and why.

**To create a pull request:**

1. Push your branch to the remote repository:
```
git push origin your-feature-branch
```
2. Navigate to the repository on GitHub
3. Click 'New pull request'
4. Select your branch from the dropdown menu
5. Click 'Create pull request'

# Code Reviews

At least one other team member should review all pull requests. Code reviews help us ensure code quality and consistency. If you're the one reviewing, remember to be constructive and respectful.

# Communication

Finally, remember that clear communication is key to a successful project. If you're unsure about something, don't hesitate to ask. Let's keep the conversation going and continue to improve our codebase!

Happy coding!

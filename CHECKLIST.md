Pre-Push Checklist for Developers

1. Local test your changes
Run the project and make sure the new feature is correctly working.
Employ automated tests to make sure all the tests pass with your changes.
Attempt to use the main user flows (e.g., login or signup) to ensure nothing is broken.
Ensure there are no warnings or errors in the terminal or browser console.
Ensure your changes are working on different browsers or devices if needed.
Get a colleague to test your changes on their machine for a second opinion.

2. Use the correct branch name and commit
Use your branch by the format feature/your-feature-name for features.
Use your branch by the format hotfix/your-fix-description for hotfixes.
Use your branch by the format bugfix/your-bug-description for bug fixes.
Pull the latest changes from the develop branch by git pull origin develop.
Make sure your branch is created on top of the latest develop branch prior to starting work.
Avoid using names like final_final or testbranch.

3. Make small, focused commits
Commit one change that makes logical sense.
Use short, descriptive commit titles like UI: update header color.
Put the area of the project in the message, for instance, API: add user endpoint.
Avoid using generic titles like fix or update.
Cluster related changes that don't blend unrelated updates within the same commit.
Use present tense when writing commit messages (e.g., Add, Fix, Update).

4. Avoid putting sensitive information
Remove passwords, API keys, or tokens from your code before committing.
Search your commit messages for any secret data.
Make sure .env files or config files with secrets aren't committed.
Commit sensitive files to .gitignore so they aren't tracked.
Double-check that no personal information (like email addresses) is exposed.
Ask a teammate to review if you’re unsure about sensitive data.

5. Follow the project’s coding style
Use the same indentation as the rest of the codebase.
Run a linter or code formatter (like ESLint or Prettier) before committing.
Write comments in the same style as existing code.
Follow naming conventions for variables and functions.
Remove unused code or commented-out blocks.
Keep code lines to the recommended length to earn 80–120 characters.

6. Limit your changes to a couple of sentences in a Pull Request (PR)
Explain in a few words what your changes do.
Add any critical details or special reviewer information.
List any new dependencies or setup instructions if added.
Identify whether your original changes fix a bug, add a feature, or modify documentation.
Use bullets for multiple changes to keep it brief.
Refer to the corresponding task or issue number in your summary.

7. Include a screenshot or test results if required
Include a screenshot for the new UI change.
Paste automated test results to show that all tests pass.
Include a GIF showcasing a new animation or interaction.
Include before-and-after images for visual changes.
Include logs or output if your change is affecting backend operations.
Include a link to a deployed preview if available.

8. Associate your PR with an issue or task
Add "Closes #123" to your PR so that it closes the corresponding issue automatically.
Use "Fixes #456" if your fix closes a bug.
Add "Related to #789" for tasks that are related but not fixed.
Include the task number or ticket number in the summary of your PR.
Tag the appropriate project or milestone if your platform has this feature.

9. Ask for a code review
Assign your PR to a colleague for review.
Tag reviewers at @username in your PR comment.
Ask for feedback in your team chat or messaging system.
Wait for at least one approval before merging.
Respond to comments and make changes if necessary.


Thank your reviewers for their feedback.
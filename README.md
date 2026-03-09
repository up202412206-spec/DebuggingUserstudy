# Debugging Study

User study evaluating debugging tools.

## Structure
- src/main/java/study/ - Your buggy code
- src/test/java/study/ - Your tests
- tools/toolA/ - Tool A candidates
- tools/toolB/ - Tool B candidates

## Build
```bash
mvn clean compile
mvn test
```

## Student Workflow
See STUDENT_INSTRUCTIONS.md

## Commits
```bash
git commit --allow-empty -m "TASK_BugA_ToolA_START: $(date +'%Y-%m-%d %H:%M:%S')"
git commit -m "TASK_BugA_ToolA_LOCALIZATION: Found bug in BugA.java line X"
git commit -m "TASK_BugA_ToolA_CORRECTION: Fix complete, all tests passing"
git push origin main
```

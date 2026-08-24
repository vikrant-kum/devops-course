# Case Statement in Bash

## 📌 What is a Case Statement?

The `case` statement in Bash is used to execute different commands
based on the value of a variable or expression.

It is useful when we have multiple possible choices.

---

## 🧠 Basic Syntax

```bash
case $variable in
    pattern1)
        commands
        ;;
    pattern2)
        commands
        ;;
    *)
        default_commands
        ;;
esac

Important Parts


| Syntax | Purpose                   |
| ------ | ------------------------- |
| `case` | Starts the case statement |
| `in`   | Begins the patterns       |
| `)`    | Ends a pattern            |
| `;;`   | Ends a case/block         |
| `*`    | Default/wildcard case     |
| `esac` | Ends the case statement   |


 Examples:

Examples for this topic are available in the examples directory.

📝 Exercises

Practice questions are available in the exercises directory.

  

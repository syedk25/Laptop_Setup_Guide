
# 1. Update Linux Mint

1. open  **Update Manager**  and install and update all
2. Open **Driver Manager** and install any recommended drivers.

or in terminal ;

```Shell
sudo apt update && sudo apt upgrade -y
```

| Command Part          | Plain English Meaning                              | Simple Analogy                          |
| --------------------- | -------------------------------------------------- | --------------------------------------- |
| **`sudo`**    | Run as administrator ("Super User Do")             | Unlocking the door with your master key |
| **`apt`**     | Your software manager tool                         | Calling the store manager               |
| **`update`**  | Check for new app versions                         | Reading the updated menu                |
| **`&&`**      | "And then" (runs the next step if the first works) | Moving to the next step                 |
| **`upgrade`** | Download and install the updates                   | Ordering and getting the food           |
| **`-y`**      | Automatically answer "Yes" to prompts              | Saying "go ahead, don't ask me again"   |

3) Set up **Timeshift** snapshots before installing development tools.

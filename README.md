# Package Sorting Solution
This repository contains a solution to the problem of sorting packages based on their dimensions and mass. The task is to determine which stack a package should go to: STANDARD, SPECIAL, or REJECTED.

# Problem Statement
Packages need to be dispatched into different stacks based on the following rules:

A package is bulky if:

Its volume (width * height * length) is greater than or equal to 1,000,000 cm³.
Or if any of its dimensions (width, height, or length) is greater than or equal to 150 cm.
A package is heavy if:

Its mass is greater than or equal to 20 kg.
Sorting Criteria:

STANDARD: Packages that are neither bulky nor heavy.
SPECIAL: Packages that are either bulky or heavy.
REJECTED: Packages that are both bulky and heavy.

## Requirements

- Python 3

# Practice Challenges

![Python module map to help you plan modular challenge projects](../assets/module-map.svg)

Try these after the matching lessons. Start with a small working version, then add error handling and tests.

## Beginner

### 1. Random quiz picker
**Modules:** `random`

Store five quiz questions in a list and select one at random. Explain why the chosen question can change between runs.

### 2. Date greeting
**Modules:** `datetime`

Print today's date and a short greeting. Keep date formatting separate from the rest of your program.

### 3. Word counter
**Modules:** `collections`

Count how many times each word appears in a sentence. Consider whether punctuation and uppercase letters should count as different words.

## Intermediate

### 4. Settings loader
**Modules:** `json`, `pathlib`

Save a theme and font size in JSON, then load them on the next run. Handle a missing or invalid settings file gracefully.

### 5. Modular grade calculator
**Your own modules**, `unittest`

Create a `grades.py` module with functions to calculate a mean and convert a score to a grade band. Put tests in a separate file.

### 6. Nearby Wi-Fi viewer improvements
**Modules:** `platform`, `subprocess`

Improve the [Wi-Fi Network Viewer](../projects/wifi-network-viewer.md). Keep the project read-only, and do not attempt to obtain passwords or bypass network security.

## Challenge checklist

- [ ] I can explain what each imported module does.
- [ ] I can run the program from a clean terminal.
- [ ] I can explain the main functions without reading every line.
- [ ] I tested a normal case and an edge case.
- [ ] I handled at least one likely error.
- [ ] I wrote down one thing I would improve next.

## Share your solution

Create a branch, add your code and a short explanation, then open a pull request. Include steps to run the program and any platform requirements.

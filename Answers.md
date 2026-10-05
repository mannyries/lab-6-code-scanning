# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?
    Answer 1.1 PyYAML 5.1
2. Which CVE is linked to this vulnerability?
    Answer 1.2 CVE-2020-14343
3. What remediation steps do you suggest?
    Answer 1.3 Upgrade PyYAML from version 5.1 to version 5.4 or newer. Applications should also avoid unsafe YAML loading methods and use safer options such as yaml.safe_load() when processing untrusted data.
### Vulnerability 2:
1. Which vulnerability are you addressing?
    Answer 2.1 Pillow 9.4.0,
2. Which CVE is linked to this vulnerability?
    Answer 2.2 CVE-2023-50447
3. What remediation steps do you suggest? 
    Answer 2.3 Upgrade Pillow from version 9.4.0 to 10.2.0 or newer, since version 10.2.0 contains the fix for this vulnerability. It is also recommended to avoid passing untrusted or user-controlled input into functions such as ImageMath.eval.

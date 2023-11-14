# PHPGrukul-Pre-School-Enrollment-System-v1.0

I wanted to touch on security vulnerabilities on phpgurukul Pre-school Enrollment System.

## Vulnerabilities

### CVE-2023-47445
**Description:** SQL Injection vulnerability on "preschool/admin/" page, "username" parameter.
**Affected Version:** 1.0
**Solution:** The values ​​in users' parameter entries must be checked and filtered out of escape characters.

### CVE-2023-47446
**Description:** Cross-Site Scripting (Stored XSS) vulnerability on Admin account settings on "profile.php" page, "fullname" parameter.
**Affected Version:** 1.0
**Solution:** Mitigate stored XSS vulnerabilities by implementing input validation and encoding user-generated content before storing it in the database.

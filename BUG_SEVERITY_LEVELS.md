# Bug Severity Levels

This document outlines the bug severity levels used in this project. Each bug is categorized into one of three levels: Critical, Major, or Minor. These levels help us prioritize bug fixes and manage the development workflow more efficiently.

## Critical

Critical bugs are severe issues that halt the operation of the application, cause data corruption, or expose security vulnerabilities. These bugs require immediate attention and should be addressed as soon as they are discovered.

**Characteristics:**
- Causes application crashes or system failure.
- Leads to data loss or corruption.
- Exposes significant security vulnerabilities.
- Affects the majority of users and major functionality with no available workaround.

**Examples:**
- A security flaw that allows unauthorized access to user data.
- A bug that causes the application to crash on startup for all users.

## Major

Major bugs significantly impact the functionality of the application but do not necessarily bring the entire system down. They can degrade the user experience or affect critical features but usually have workarounds.

**Characteristics:**
- Impairs major functionality but does not cause a complete failure.
- Affects a large portion of users but not all.
- Workarounds are available but not ideal.

**Examples:**
- A feature that is not working as documented for many users.
- Performance issues that severely degrade the user experience.

## Minor

Minor bugs have a minimal impact on the application's functionality and user experience. These are often cosmetic issues or small glitches that do not significantly impair the application's overall operation.

**Characteristics:**
- Affects a small number of users.
- Does not significantly impact the application’s performance or functionality.
- Cosmetic issues, such as typos, alignment issues, or incorrect UI elements.

**Examples:**
- A spelling mistake in the user interface.
- A UI element that is misaligned but does not affect functionality.

---

We encourage contributors to prioritize the resolution of bugs based on their severity level. For any queries or further classification of a bug, please reach out to the core team in our [Discord](https://discord.gg/Zx3bbkeGmY).
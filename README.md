# AcademyBugs - Top 8 Critical Bugs - Manual QA Portfolio
**Tester:** Mohsin Ishfaq | **Date:** Aug 5, 2026 | **URL:** https://academybugs.com/find-bugs/
**Test Cases:** 20 (12 Pass, 8 Fail) | **Bugs:** Top 8 Critical (4 Crashes, 2 Functional, 1 Filter, 1 Performance)

## Overview
Exploratory testing on AcademyBugs Find Bugs page which has 25 bugs planted. I focused on Top 8 High severity genuine bugs that matter for e-commerce clients.

## Top 8 Bugs Summary
- BUG-01 [High] Cart quantity stuck at 2 - Update fails
- BUG-02 [High] Grand total random, not sum
- BUG-03 [High] Filter by Price broken
- BUG-04 [High] Order History infinite loading
- BUG-05 [High Crash] Currency change freezes page
- BUG-06 [High Crash] View 10/25/50 freezes page
- BUG-07 [High Crash] Post comment freezes page
- BUG-08 [High Crash] Forgot Password freezes page

## Evidence

### BUG-01: Quantity stuck at 2
![BUG-01](06_Evidence/Screenshots/BUG_01_quantity-stuck-at-2.png)

### BUG-02: Grand total calculation wrong
![BUG-02](06_Evidence/Screenshots/BUG_02_grand-total-random.png)

### BUG-03: Filter by Price broken
![BUG-03](06_Evidence/Screenshots/BUG_03_filter-price-broken.png)

### BUG-04: Order History infinite loading
![BUG-04](06_Evidence/Screenshots/BUG_04_order-history-infinite-loading.png)

### BUG-05: Currency freeze - CRASH VIDEO
https://github.com/mohsin-ishfaq/academybugs-top8-critical-bugs-qa-portfolio/blob/main/06_Evidence/Videos/BUG_05_currency-freeze-changing-currency.mp4

### BUG-06: View click freeze - CRASH VIDEO
https://github.com/mohsin-ishfaq/academybugs-top8-critical-bugs-qa-portfolio/blob/main/06_Evidence/Videos/BUG_06_view-click-freeze.mp4

### BUG-07: Comment freeze - CRASH VIDEO
https://github.com/mohsin-ishfaq/academybugs-top8-critical-bugs-qa-portfolio/blob/main/06_Evidence/Videos/BUG_07_comment-freeze-post-comment.mp4

### BUG-08: Forgot password freeze - CRASH VIDEO
https://github.com/mohsin-ishfaq/academybugs-top8-critical-bugs-qa-portfolio/blob/main/06_Evidence/Videos/BUG_08_forgot-password-freeze.mp4

## Documents
- Test Plan: `01_Test_Plan/`
- Test Cases 20: `02_Test_Cases/AcademyBugs_20_TestCases_Realistic_Aug5_2026.xlsx`
- Bug Reports Top 8: `03_Bug_Reports/AcademyBugs_TOP8_Bugs_Genuine_Aug5_2026.xlsx`
- RTM: `04_RTM/`
- Test Summary: `05_Test_Summary/`

## Tools
Chrome DevTools, ShareX, Snippet tool, Excel

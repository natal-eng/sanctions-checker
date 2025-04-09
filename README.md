
# Sanctions Checker

ממשק לבדיקה אם כתובת קריפטו מופיעה ברשימות סנקציות באמצעות API של Chainalysis.

## מבנה הפרויקט:

```
/sanctions-checker
├── api
│   └── check.js     ← פונקציה בשרת לקריאת Chainalysis
└── index.html       ← ממשק המשתמש (React או HTML)
```

## הוראות:

1. העלה את שני הקבצים לריפו שלך ב-GitHub.
2. ודא ש-Vercel מזהה את התיקייה כפרויקט מסוג `Other`.
3. הקריאה תתבצע מהקליינט דרך `/api/check?address=<כתובת>` והשרת יעשה את הקריאה ל-Chainalysis.

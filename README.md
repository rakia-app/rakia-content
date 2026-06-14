# rakia-content

תוכן מוכן־מראש (pre-built) לאפליקציית Rakia. הקבצים מתפרסמים כ-**Release assets** (לא ב-tree, כדי לא לנפח את היסטוריית הגיט).

## הורדה

מ-Release האחרון: `https://github.com/rakia-app/rakia-content/releases/latest/download/<file>`

## קבצים

- `milon-hareiyah-bundle.json.gz` — מילון הראי"ה (הרב יוסף קלנר): ספר HTML + ערכי content/ref + רשת ראו_גם.
- `kovetz-yesodot-bundle.json.gz` — קובץ יסודות וחקירות (Sefaria): 1167 ערכים לפי אות + מבוא/הקדמה + קשרי "עיין ערך".

בנייה חוזרת: `rakiaBuildMilonHareiyah()` / `rakiaBuildReferenceWork('<sourceKey>')` ב-DevTools של Rakia, ואז העלאת ה-.gz ל-Release חדש.

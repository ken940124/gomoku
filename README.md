# 五子棋對弈

線上玩：https://ken940124.github.io/gomoku/

- **對戰 AI**：瀏覽器內建的 minimax + alpha-beta + VCF/VCT 引擎
- **雙人對局**：本機輪流下，或建立好友房間用 6 碼代碼遠端對戰
- 支援標準連珠禁手、悔棋、復盤與 AI 找轉折點

不需要登入。線上房間和匿名棋譜記錄使用 Firebase（匿名登入 + Realtime Database），資料庫規則見 `database.rules.json`。

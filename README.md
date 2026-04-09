# Rogue like Deck Building Simple Chess Game   

 https://yeohs0212.github.io/chessmantle/


# ♟️ Chess Roguelike: Daily Challenge

**Deckbuilding × Chess × Roguelike**
A daily turn-based strategy game that combines the tactical movement of chess with deckbuilding mechanics and a procedural reward system. Every day, a new seed generates a unique board—and everyone around the world plays the exact same puzzle!

🎮 **[Play the Daily Challenge Here]( https://yeohs0212.github.io/chessmantle/)** 

<br>

## 🌟 The Daily Mode
* 🗓️ **Daily Seeded Runs:** Every 24 hours at midnight, the enemy placements and reward pools reset based on the date. Compete with your friends to see who can clear it in the fewest turns!
* ⚖️ **Dynamic Budget System:** Enemy pieces are procedurally spawned using a point-based budget (Stage 1: 14pts ➔ Stage 3: 30pts), ensuring a perfectly balanced but highly randomized challenge every day.
* 🔄 **Infinite Retries:** Made a critical mistake? Game Over? No problem! You can retry the same daily seed as many times as you want until you master the puzzle.
* 📊 **Share Your Results:** Wordle-style shareable results! Easily copy your daily victory to your clipboard and flex in your group chats.
  > ♟️ Chess Roguelike Daily (4/9)
  > 🟩 Stage 1: 3 turns
  > 🟩 Stage 2: 5 turns
  > 🟩 Stage 3: 4 turns

<br>

## 📜 How to Play
1. **Goal:** Survive and checkmate the enemy King across **3 rapid-fire stages**.
2. **Action Points (AP):** You are given **1 AP** per turn. Spend it to either **move** a piece on the board or **summon** a card from your hand onto an empty square near your King.
3. **Draw & Grow:** Every time you capture an enemy piece, you draw 1 card.
4. **Deckbuilding Mechanics:** * **Upgrade:** Collect 3 identical common cards to permanently upgrade them into pieces with special abilities (e.g., *Rampage Rook* that pierces through enemies).
   * **Compress:** Banish weak cards from your graveyard to optimize your deck.
   * **Perks:** Choose legendary rewards to expand your King's movement or gain a protective shield.

<br>

## 🤖 Dynamic AI
* Powered by a custom **Minimax algorithm (+Alpha-Beta Pruning)**.
* Evaluates optimal moves using Piece-Square Tables (PST) and piece values, calculating up to depth 4 for a fast yet challenging opponent.

<br>

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Architecture:** Zero dependencies. Runs lightning fast as a single HTML file without any heavy frameworks.
* **Deployment:** GitHub Pages

<br>

## 👨‍💻 Developer
* **Created by:**  yeohs0212

# ♟️ Chess Roguelike: 데일리 챌린지

**덱빌딩(Deckbuilding) × 체스(Chess) × 로그라이크(Roguelike)**
매일 새로운 시드(Seed)로 생성되는 퍼즐을 전 세계 사람들과 동일하게 플레이할 수 있는 턴제 전략 게임입니다. 체스의 전술적 움직임, 덱빌딩의 성장 요소, 로그라이크의 무작위 보상 시스템을 하나로 결합했습니다!

🎮 **[게임 플레이하기] https://yeohs0212.github.io/chessmantle/** 

<br>

## 🌟 데일리 모드 핵심 기능
* 🗓️ **매일 바뀌는 시드:** 매일 자정(24시간)마다 날짜를 기준으로 적의 배치와 보상 풀이 새롭게 바뀝니다. 친구들과 누가 더 적은 턴 수로 클리어하는지 경쟁해 보세요!
* ⚖️ **동적 예산 시스템 (Budget System):** 1스테이지(14점)부터 3스테이지(30점)까지 정해진 '포인트 예산' 내에서 무작위로 적 기물을 사 와서 배치합니다. 매일 완벽하게 밸런스가 맞춰진, 하지만 전혀 다른 조합의 퍼즐을 즐길 수 있습니다.
* 🔄 **무한 재도전:** 치명적인 실수를 했거나 게임 오버를 당했나요? 문제없습니다! 클리어할 때까지 오늘 날짜의 동일한 배치로 몇 번이든 다시 도전하며 공략을 깎아나갈 수 있습니다.
* 📊 **결과 공유하기:** 워들(Wordle) 스타일의 결과 공유 기능을 지원합니다! 클리어 후 결과를 복사해 단톡방에 자랑해 보세요.
  > ♟️ 체스 로그라이크 데일리 (4/9)
  > 🟩 Stage 1: 3턴
  > 🟩 Stage 2: 5턴
  > 🟩 Stage 3: 4턴

<br>

## 📜 게임 규칙 (How to Play)
1. **승리 목표:** 총 **3개의 스테이지**에서 살아남고 적의 킹을 체크메이트하세요.
2. **행동력 (AP):** 턴마다 **1의 행동력**이 주어집니다. 행동력을 소비해 보드 위 기물을 **이동**하거나, 손패의 카드를 킹 주변 빈 공간에 **배치(소환)**할 수 있습니다.
3. **드로우 & 성장:** 적 기물을 잡을 때마다 덱에서 카드를 1장 뽑습니다.
4. **덱빌딩 요소:**
   * **강화 (Upgrade):** 같은 일반 등급 카드 3장을 모아 특수 능력이 있는 강력한 기물(예: 적을 뚫고 돌진하는 *돌진룩*)로 영구 강화합니다.
   * **압축 (Compress):** 묘지에 있는 약한 카드를 영구 제거하여 덱을 최적화합니다.
   * **강화 효과 (Perks):** 전설/희귀 보상을 통해 킹의 이동 범위 및 소환 범위를 늘리거나, 체크메이트를 1회 막아주는 방어막을 얻을 수 있습니다.

<br>

## 🤖 동적 난이도 AI
* **Minimax 알고리즘 (+Alpha-Beta Pruning)** 기반의 커스텀 AI가 탑재되어 있습니다.
* 기물 가치와 위치 점수(Piece-Square Tables)를 평가하여, 최대 Depth 4까지의 수를 읽고 빠르고 위협적인 최적의 수를 둡니다.

<br>

## 🛠️ 기술 스택 (Tech Stack)
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **No Frameworks:** 무거운 프레임워크나 외부 라이브러리 없이, 단일 HTML 파일로 번개처럼 빠르게 동작합니다.
* **Deployment:** GitHub Pages

<br>

## 👨‍💻 제작자
* **Developer:** yeohs0212
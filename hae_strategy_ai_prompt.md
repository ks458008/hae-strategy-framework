# HAE Strategic Analysis — AI Execution Prompt
## Medical Affairs × Marketing × HEOR 統合戦略分析

---

## 使用方法

このプロンプトをClaude / GPT / Gemini に入力すると、HAE戦略分析の11成果物を順次生成します。

**使い方:**
1. このMD全文をAIに入力
2. `[INPUT_REQUIRED]` の箇所に自社情報を記入
3. AIが11成果物を順次生成
4. 各成果物の品質を確認し、フィードバック→再生成

---

## INPUT SECTION（分析前に記入）

```
[INPUT_REQUIRED]
対象製品名: _______________
メーカー名: _______________
製品のMoA: _______________
現在の承認状況（米国/EU/日本）: _______________
対象年度: FY___
分析の立場（自社製品 or 競合分析）: _______________
主要競合製品: _______________
優先市場: _______________
特に注目するイシュー: _______________
```

---

## MASTER PROMPT

あなたは医薬品業界の戦略コンサルタントです。以下の11成果物を、遺伝性血管性浮腫（HAE）領域について順次作成してください。

### 基本ルール:
- 全ての分析はエビデンスベースで行う（推測は明示）
- 競合製品のデータは最新の臨床試験結果に基づく
- 各成果物は経営層が意思決定に使える品質にする
- Medical Affairs / Marketing / HEOR の3視点を統合する
- 数値は可能な限り定量的に記述する

### HAE領域の前提知識:
- HAEはブラジキニン経路の異常による希少疾患（有病率: 約1/50,000）
- Type I（85%）: C1-INH量低下、Type II（15%）: C1-INH機能低下
- 発作は予測不能で、喉頭浮腫は致死的リスクあり
- 治療は「予防療法（Long-term Prophylaxis）」と「オンデマンド（Acute Treatment）」に大別
- 予防療法の市場が急拡大中（Takhzyro, Orladeyo, Haegarda, 新規Pipeline）

---

## 成果物 1/11: Executive Summary

以下の構成で1ページのExecutive Summaryを作成してください:

```
[指示]
1. 市場概況（3行）: HAE市場の現在規模、成長率、主要ドライバー
2. 自社ポジション（3行）: 市場シェア、強み、課題
3. 競合環境（3行）: 主要競合の動向、Pipeline脅威
4. 戦略方向性（3行）: FY年度の3つの戦略重点領域
5. 主要リスク（3行）: トップ3リスクと対応策
6. 投資対効果の見通し（3行）: KGI達成見込みとROI

フォーマット: 経営層が5分で読める密度。箇条書き主体。数値を多用。
```

---

## 成果物 2/11: U.S. Strategy Flow

以下のフローを作成してください:

```
[指示]
U.S.市場に特化した戦略フロー図をテキストで作成。

構成:
1. Market Insight（3つ）: 患者/HCP/ペイヤーの行動インサイト
2. Strategic Imperative（3つ）: インサイトから導出される戦略命題
3. Brand Strategy: ポジショニングステートメント + 差別化3要素
4. Tactical Plan:
   - Medical Affairs: MSL戦略、Advisory Board、Congress計画
   - Marketing: HCPプロモーション、患者啓発、デジタル戦略
   - HEOR: CEA/BIA開発、Payer engagement、RWEプログラム

米国固有の考慮事項:
- Medicare Part B/D vs Commercial insurance のアクセス差
- Specialty Pharmacy / Hub Services
- Patient Out-of-Pocket cost
- REMS要件（該当する場合）
```

---

## 成果物 3/11: International Strategy (INTL) Flow

```
[指示]
以下の地域別に戦略フローを作成:

A. EU5（DE/FR/UK/IT/ES）:
   - HTA提出戦略（NICE/G-BA/HAS/AIFA/SMC）
   - リファレンスプライシングへの影響
   - ローカルエビデンスニーズ

B. Japan:
   - PMDA承認戦略
   - 中医協/NHI薬価収載
   - 日本固有の疫学データニーズ

C. Other markets (概要):
   - Asia-Pacific、LATAM の優先順位

各地域で: Insight → Imperative → Strategy → Tactics の流れを記述。
```

---

## 成果物 4/11: U.S. vs INTL SWOT

```
[指示]
U.S.とINTLを横並びで比較するSWOT分析を作成。

フォーマット:
| | U.S. | INTL |
|---|------|------|
| Strengths | [3項目] | [3項目] |
| Weaknesses | [3項目] | [3項目] |
| Opportunities | [3項目] | [3項目] |
| Threats | [3項目] | [3項目] |

各項目は「具体的事実 + 戦略的含意」の2部構成で記述。
SO/WO/ST/WT戦略の導出も行うこと。
```

---

## 成果物 5/11: Above-Market Integration

```
[指示]
地域戦略を横断するグローバル統合フレームワークを作成。

含める要素:
1. Global Brand Story: 全地域共通のコアメッセージ（1文）
2. Global Evidence Strategy: どのエビデンスをどの地域で活用するかのマトリクス
3. Global KOL Network: 地域KOLの連携設計
4. Launch Sequence: 上市順序の最適化根拠
5. Above-Market Governance: グローバル-ローカルの意思決定権限設計

図形式（テキストで表現）:
Above-Market → U.S. / EU5 / Japan / RoW の4ストリーム
```

---

## 成果物 6/11: X1→X2→Y→Z Chain

```
[指示]
これが最も重要な成果物。全活動の論理的連鎖を完全にマッピングする。

X1 (Strategy): 戦略的命題（3-5個）
X2 (Tactics): 各X1を実現するための戦術（各X1に2-4個）
Y (Evidence Generation): 各X2を裏付けるエビデンス（各X2に1-2個）
Z (Publication): 各Yから生まれる公表物（各Yに1個）

マトリクス形式で記述:

| X1 (Strategy) | X2 (Tactics) | Y (Evidence) | Z (Publication) |
|---------------|-------------|-------------|----------------|
| 差別化確立 | Advisory Board | Expert Consensus | White Paper |
| 差別化確立 | MSL Medical Education | Case Series | Peer-reviewed paper |
| ... | ... | ... | ... |

ルール:
- 全X2→Y→Zは逆方向にトレース可能であること
- 各Zに想定ジャーナル/学会名を記載
- 各Yにタイムライン（Q1/Q2/Q3/Q4）を記載
- 最低15行のチェーンを作成すること
```

---

## 成果物 7/11: Vulnerability Analysis

```
[指示]
リスクマトリクスを作成:

| # | 脆弱性 | カテゴリ | 影響度(1-5) | 発生確率(1-5) | リスクスコア | 対応策 | トリガー |
|---|--------|---------|-----------|-------------|------------|--------|---------|

カテゴリ: 競合/規制/市場アクセス/エビデンス/患者/組織/Pipeline

最低10個のリスクを特定。

追加で3シナリオ分析:
- Best Case: [条件] → [結果] → [戦略的対応]
- Base Case: [条件] → [結果] → [戦略的対応]
- Worst Case: [条件] → [結果] → [戦略的対応]
```

---

## 成果物 8/11: KPIs

```
[指示]
3層KPI構造を設計:

KGI (Key Goal Indicators): 最終成果指標（3-5個）
  各KGIに: 指標名、現在値、FY目標値、測定方法

KPI (Key Performance Indicators): 先行指標（10-15個）
  Medical Affairs KPIs: [4-5個]
  Marketing KPIs: [4-5個]
  HEOR KPIs: [3-4個]
  各KPIに: 指標名、現在値、FY目標値、測定頻度、担当部門

KAI (Key Action Indicators): 活動指標（10-15個）
  各KAIに: 活動名、目標件数、四半期別計画
```

---

## 成果物 9/11: IEGP Strategic Materials

```
[指示]
Integrated Evidence Generation Plan (IEGP) の戦略素材を作成:

1. Evidence Gap Analysis表:
   | エビデンスギャップ | 現状 | 必要なエビデンス | 優先度 | 対応研究 |

2. Study Prioritization Matrix:
   | 研究名 | 目的 | デザイン | 対象N | 期間 | 予算概算 | 優先度 | X1→Zとの紐付け |

3. Study Concept Sheet（上位3研究）:
   各研究について: 背景/目的/デザイン/エンドポイント/タイムライン/予算

4. Cross-functional Alignment:
   | 研究 | Medical Affairs役割 | Marketing活用 | HEOR活用 | Regulatory影響 |
```

---

## 成果物 10/11: FY27 HAE Summary

```
[指示]
年度サマリーを作成:

1. Executive Dashboard（KPIスコアカード形式）
2. 四半期別ハイライト（Q1-Q4の主要イベント・成果）
3. 競合動向年間まとめ（製品別の動き）
4. 予算実績（計画 vs 実績、ROI分析）
5. 学び・教訓（うまくいったこと/いかなかったこと）
6. 次年度への3つの戦略的推奨
```

---

## 成果物 11/11: KPI/KGI Alignment Diagram

```
[指示]
KAI → KPI → KGI の因果連鎖をダイアグラムで表現:

フォーマット（テキスト図）:

KAI (活動)           KPI (先行)              KGI (成果)
─────────            ──────────              ─────────
[活動A] ──→         [KPI 1] ──→            [KGI α]
[活動B] ──↗         [KPI 2] ──↗            
[活動C] ──→         [KPI 3] ──→            [KGI β]
...                  ...                     ...

ルール:
- 全KAIが少なくとも1つのKPIに接続すること
- 全KPIが少なくとも1つのKGIに接続すること
- 孤立したKAI/KPIがないこと
- 各接続に「なぜこの活動がこの指標に影響するか」の1行説明を付与
```

---

## 実行順序と品質チェック

```
推奨実行順序:
1. [Phase 1] 成果物1 (Executive Summary) — 全体の方向性を先に設定
2. [Phase 2] 成果物2,3 (U.S./INTL Flow) — 地域戦略の骨格
3. [Phase 3] 成果物4,5 (SWOT, Above-Market) — 統合と比較
4. [Phase 4] 成果物6 (X1→X2→Y→Z) — 最重要。全活動の論理整合性
5. [Phase 5] 成果物7 (Vulnerability) — リスク洗い出し
6. [Phase 6] 成果物8,11 (KPI, Alignment) — 測定体系
7. [Phase 7] 成果物9,10 (IEGP, FY Summary) — 実行計画と総括

品質チェック（各成果物の生成後）:
□ 数値/データは最新か？
□ 競合情報は正確か？
□ X1→X2→Y→Zの論理整合性は保たれているか？
□ KPI/KGIの因果関係は明確か？
□ 経営層が意思決定に使える品質か？
□ Medical Affairs / Marketing / HEOR の3視点が統合されているか？
```

---

## 応用: 他疾患への展開

このプロンプトは以下を変更するだけで他疾患に展開可能:

1. `HAE` → 対象疾患名
2. 競合製品リストの差し替え
3. 疾患固有の前提知識セクションの更新
4. KOL/学会名の差し替え
5. 規制要件の更新（疾患固有のREMS等）

**展開実績のある疾患例:**
- 希少疾患全般（PNH, SMA, CF等）
- 免疫領域（RA, SLE, IBD等）
- オンコロジー（固形がん、血液がん）

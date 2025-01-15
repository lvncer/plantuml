# PlantUML

_All these sample images are taken from [https://www.uml-diagrams.org/index-examples.html](https://www.uml-diagrams.org/index-examples.html).Thanks._

UML（Unified Modeling Language）は、ソフトウェア開発やシステム設計で使われるモデリング言語で、システムの構造や振る舞いを視覚的に表現するために用いられます。UML には以下のような種類の図（ダイアグラム）があり、それぞれ異なる目的に応じて使用されます。

## Agenda

- **1. 構造図（Structure Diagrams）**

  1. **クラス図 (Class Diagram)**

  2. **コンポーネント図 (Component Diagram)**

  3. **オブジェクト図 (Object Diagram)**

  4. **配置図 (Deployment Diagram)**

  5. **パッケージ図 (Package Diagram)**

  6. **プロファイル図 (Profile Diagram)**

- **2. 振る舞い図（Behavior Diagrams）**

  1. **ユースケース図 (Use Case Diagram)**

  2. **アクティビティ図 (Activity Diagram)**

  3. **ステートマシン図 (State Machine Diagram)**

  4. **相互作用概観図 (Interaction Overview Diagram)**

- **3. 相互作用図（Interaction Diagrams）**

  1. **シーケンス図 (Sequence Diagram)**

  2. **コミュニケーション図 (Communication Diagram)**

  3. **タイミング図 (Timing Diagram)**

  4. **相互作用図 (Interaction Diagram)**

## **1. 構造図（Structure Diagrams）**

システムの静的な構造を表現するための図。

### 1. **クラス図 (Class Diagram)**

- システムのクラスとその関係を表現します。
- 属性、メソッド、クラス間の関連、継承、依存などを記載。

- <img src="https://www.uml-diagrams.org/thumbnails/online-shopping-user-login-uml-object-diagram-example.png" alt="class-example" width="400">

### 2. **コンポーネント図 (Component Diagram)**

- システムを構成するコンポーネント（モジュール）の構造を示します。
- ソフトウェアモジュールやその依存関係を表現。

- <img src="https://www.uml-diagrams.org/thumbnails/online-shopping-uml-component-diagram-example.png" alt="component-example" width="400">

### 3. **オブジェクト図 (Object Diagram)**

- システム内の具体的なオブジェクトのインスタンスとその関係を示します。
- クラス図の具体例。

- <img src="https://www.uml-diagrams.org/examples/object-example-login-controller.png" alt="object-example" width="400">

### 4. **配置図 (Deployment Diagram)**

- システムのハードウェア構成とソフトウェアの配置を表現。
- ノード（サーバーや端末）とその間の通信を表現。

- <img src="https://www.uml-diagrams.org/thumbnails/web-application-uml-manifest-diagram-example.png" alt="deployment-example" width="400">

### 5. **パッケージ図 (Package Diagram)**

- システム内の要素を論理的なグループ（パッケージ）にまとめ、依存関係を表します。

- <img src="https://www.uml-diagrams.org/thumbnails/multi-layered-web-architecture-uml-package-diagram-example.png" alt="package-example" width="400">

### 6. **プロファイル図 (Profile Diagram)**

- UML の標準メタモデルを拡張するための構造を表現。

- <img src="https://www.uml-diagrams.org/thumbnails/soaml-uml-profile-diagram-example.png" alt="profile-example" width="400">

## **2. 振る舞い図（Behavior Diagrams）**

システムの動的な振る舞いや動きを表現するための図。

### 1. **ユースケース図 (Use Case Diagram)**

- システムの外部から見た機能や、アクター（利用者）とその相互作用を表現。

- <img src="https://www.uml-diagrams.org/thumbnails/online-shopping-use-case-diagram-example.png" alt="usecase-example" width="400">

### 2. **アクティビティ図 (Activity Diagram)**

- ワークフローやプロセスの流れを表現。
- 条件分岐や並列処理を記載。

- <img src="https://www.uml-diagrams.org/thumbnails/online-shopping-uml-activity-diagram-example.png" alt="activity-example" width="400">

### 3. **ステートマシン図 (State Machine Diagram)**

- オブジェクトの状態遷移を表現。
- イベントやアクションによる状態の変化を記載。

- <img src="https://www.uml-diagrams.org/thumbnails/online-shopping-user-account-state-diagram-example.png" alt="statemachine-example" width="400">

### 4. **相互作用概観図 (Interaction Overview Diagram)**

- アクティビティ図の一種で、相互作用の流れを概観。

- <img src="https://www.uml-diagrams.org/thumbnails/online-shopping-uml-interaction-overview-diagram-example.png" alt="interaction-overview-example" width="400">

---

## **3. 相互作用図（Interaction Diagrams）**

システム内の要素間の相互作用を表現するための図。

### 1. **シーケンス図 (Sequence Diagram)**

- 時間軸に沿ってオブジェクト間のメッセージ交換を表現。

- <img src="https://www.uml-diagrams.org/thumbnails/facebook-authentication-uml-sequence-diagram-example.png" alt="sequence-example" width="400">

### 2. **コミュニケーション図 (Communication Diagram)**

- オブジェクト間のメッセージ交換とその関係を表現。
- シーケンス図に似ていますが、メッセージの流れよりも関連性を重視。

- <img src="https://www.uml-diagrams.org/thumbnails/online-shopping-uml-communication-diagram-example.png" alt="communication-example" width="400">

### 3. **タイミング図 (Timing Diagram)**

- 時間に沿った状態変化を表現。
- 特定のオブジェクトの振る舞いを追跡。

- <img src="https://www.uml-diagrams.org/thumbnails/alzheimers-uml-timing-diagram-example.png" alt="timing-example" width="400">

### 4. **相互作用図 (Interaction Diagram)**

- シーケンス図、コミュニケーション図、タイミング図を包含する。

## UML の主な活用例

- **要件定義**：ユースケース図
- **設計**：クラス図、コンポーネント図
- **プロセス分析**：アクティビティ図
- **動作確認**：シーケンス図、ステートマシン図

必要に応じて適切な図を選んで利用することが、効率的なシステム設計につながります！

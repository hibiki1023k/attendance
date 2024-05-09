# W-PLUS

## コンセプト
> 「誰でも使えるシンプルな勤怠管理アプリ」

## 機能
機能は大きく分けて２つに分かれています
1. 勤怠登録
2. 勤怠管理

## 仕様
- 事業所 >> 職場 >> 従業員の構造
- 事業所の管理者（admin）、職場の管理者（manager）、従業員（employee）が存在
- 勤怠登録を行うのはmanager, employeeのみ

## 勤怠登録
勤怠登録では以下の項目を選択して勤怠を登録します
- 日付
- 開始時刻
- 終了時刻

また、adminやmanagerは勤怠の対象となる従業員として以下の項目を選択します

### admin
- 事業所内のすべてのemployee

### manager
- 同じ職場に属するemployee、manager

## 勤怠管理
勤怠管理では登録した勤怠を以下の項目を表示します
- 従業員名
- 職場名
- 日付
- 開始時刻
- 終了時刻
- 削除ボタン

また、表示する勤怠は役職により以下の通りになります
### admin
- 事業所内のすべてのemployeeの勤怠
### manager
- 同じ職場に属するemployee、managerの勤怠
### employee
- 自分の勤怠

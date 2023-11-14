# its-hondana

## 概要
ITSの技術書を管理するライブラリの開発。

## 手順
1. docker compose up -d
2. docker exec -it its-hondana-web-1 bash
3. composer create-project "laravel/laravel=10.*" webApp
4. docker compose down
5. docker compose up -d
6. docker exec -it its-hondana-web-1 bash
7. chmod -R 777 strage/
8. localhost:8888 にアクセスするとLaravelのウェルカムページが表示される。

## 採用技術
PHP8.2, Laravel10
TypeScript, Vue.js3
Inertia.js
Docker

## メモ
今持っているPCのスペック的にLaravelプロジェクト作成時に4つほどインストールエラーが発生する。
エラーが発生したら、`composer install`を実行すると解決可能。
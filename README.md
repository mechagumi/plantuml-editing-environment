# PlantUML-Editing-Environment

## 概要

Visual Studio Codeの[Remote Development拡張機能](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)を用いたPlantUMLの編集環境です。

## 前提条件

以下の環境が必要です。

- Docker
- Visual Studio Code
  - Remote Development拡張機能

## 使用方法

以下の手順を経ると、[PlantUML拡張機能](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml)が有効化された環境が立ち上がります。

1. Visual Studio Codeを起動します。
2. コマンドパレット(`Ctrl + Shift + P`)から「Remote-Containers: Open Folder in Container...」を選択します。
3. 当リポジトリのクローン先のフォルダを選択して開きます。

## クイックスタート

sample.puを開き、コマンドパレットから「PlantUML: Preview Current Diagram」を選択してください。
PlantUMLによって生成された画像がプレビューされます。

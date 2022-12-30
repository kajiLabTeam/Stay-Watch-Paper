# Devcontainer for LaTeX

VS Code Dev Containersの機能を用いて、LaTeX環境を容易に構築する
レジュメのテンプレートと卒論のテンプレートがあります

参考記事
https://korosuke613.hatenablog.com/entry/2019/06/24/171246
参考リポジトリ
https://github.com/kajiLabTeam/Dev-Container-Tex-Template

Dockerイメージは、[ubuntu-texlive-ja](https://hub.docker.com/r/korosuke613/ubuntu-texlive-ja)を利用しています。

(**Dockerが必要です**)

## setup

1. `git clone git@github.com:kajiLabTeam/Dev-Container-Tex-Template.git`
2. VS Codeで`git@github.com:kajiLabTeam/Dev-Container-Tex-Template.git`を開く。
3. 拡張機能[Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)を追加する。
4. 左下の`><`アイコンを押して、`Open in Cotainer`を実行する。
5. コンテナ起動まで待つ
6. サイドバーのTexアイコンを押してBuild Latex Projectを押すとpdfが出力される。Texアイコンを出すにはTexファイル開く必要があるかもしれない





# ReinforceLearningNotebooks

強化学習のjupyter notebooksを書き留めておくためのリポジトリです。

## [keras-rl-Pacman.ipynb](./keras-rl-Pacman.ipynb)

keras-rlを使ってPacman(Game)をDQNで強化学習します。
入力はGame画面です。bokehを使って学習曲線をインタラクティブに更新します。
jupyterが立ち上がっている限りは学習の中断・再開は可能です。
人手で正解データを作成できるようにインタラクティブモードを作成しています。

## [timeseries.ipynb](./timeseries.ipynb)

時系列予測の手法比較です。自動売買を試すための素性に利用する予定です。
ピンポイント予測でなく予測区間を予測できるように工夫しています。

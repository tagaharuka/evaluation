森川一穂 MORIKAWA Kazuho

主観評価スクリプトの使い方
（Chrome, Firefoxでは動作を確認しました）

1. 音声ファイルを保存するディレクトリを作成する。（例：wav）


2. 各音声ファイルを次の規則で命名し、作成したディレクトリに保存する。

	[音声の名前(prefix)]_[手法の名前(suffix)].wav
	（例：	001_methodA.wav, 002_methodA.wav, 003_methodA.wav,
		001_methodB.wav, 002_methodB.wav, 003_methodB.wav）

	※参照音声を用いる場合、参照音声も適当なsuffix（例：tar）をつけて保存する。


3. 音声(prefix)の名前のリストと手法の名前のリストを作成する。

	（例：name.txt）
		001
		002
		003
	（例：method.txt）
		methodA
		methodB


4. .jsの設定部分を必要に応じて変更する。


5. .htmlの<title>や注意書きを必要に応じて変更する。
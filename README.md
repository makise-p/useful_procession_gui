# useful_procession_gui
The tool for labeling dataset for object detection as Faster R-CNN or SSD

slowsingleさんがgithubにUpdateしていたコードをアレンジしたもので、
R-CNNやYOLO,SSDなど、画像のどこに何があるのかを識別するタスクのためのラベル付与を支援するソフトウェア。

動かす前にすること
mainGUI.pdeとgetImage.pdeとprocessXML.pdeとxmlフォルダは同じフォルダ内に入れる（mainGUI.pdeを開くとmainGUIフォルダが作られるので、そのフォルダに他のものを入れる）
mainGUIの178行目のreplaceFileに保存したい場所のパスを入力
getImageの10行目に開きたい画像があるフォルダのパスを入力

・動作環境
　・windows8/macOS Mojave
　・Processing 3.3.7

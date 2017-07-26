# 將 Cordova Project 匯入 Visual Studio
微軟官方解說
https://taco.visualstudio.com/en-us/docs/migrate-to-vs2015/

摘要：
先在 Visual Studio 開一個 Cordova專案，
接著檔案 -\> 建立新檔案 -\> 從現有專案匯入 -\> 選擇 Apache Cordova類型專案 -\>下一步。
如果不能指定為 Apache Cordova那就表示沒有安裝  Visual Studio Tools for Apache Cordova的意思。

![][image-1]

接著指向原本的 Cordova Project根目錄，Cordova Project要記得放在本機目錄，不是網路目錄。  

![][image-2]
  
幫自己的 Cordova Project 設定新名字，Visual Studio就會開始轉換了。

[image-1]:	https://github.com/isaac-joe/import_Cordova_to_VisualStudio/blob/master/create-wizard.png
[image-2]:	https://github.com/isaac-joe/import_Cordova_to_VisualStudio/blob/master/create-specify-root.png
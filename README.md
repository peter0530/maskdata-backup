## maskdata備份說明

1.本資料來源為```衛生福利部中央健康保險署```opendata

2.根目錄下***maskdata.csv***與衛生福利部資料相同

3.```hostory```中為每次進行同步時保存(以天為單位分資料夾),檔案名稱格式為```maskdata_yyyy-mm-dd-His.csv```

4.```compressed``` 中為**history** 每天資料夾壓縮檔案

5.另有GoogleDrive檔案=>[連結](https://drive.google.com/open?id=1ziRaMfqEBLwh9S96PMlS2At0uSGUo8qq "GoogleDrive連結")

## 檔案解壓縮方法
***
#### Windows系統

可使用[7-ZIP](https://www.developershome.com/7-zip/download.asp "7-ZIP下載頁面")來解壓縮(會先解出yyyy-mm-dd.tar再對他解壓縮就可以得到檔案)

#### MacOS
使用指令```tar -Jxf filename.tar.xz```即可

#### Linux系統

使用指令```tar Jxvf FileName.tar.xz```即可

註:需安裝tar套件

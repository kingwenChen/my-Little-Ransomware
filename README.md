# my-Little-Ransomware

這是 [SITCON 2016](http://sitcon.org/2016/#target-home) 上針對勒索軟體演講的一個開源時做驗證 PoC

Slide: [防毒擋不住？勒索病毒猖獗與實作](http://www.slideshare.net/MaHauo/ss-59732934)

直播紀錄: [SITCON216-R2-05.防毒擋不住？勒索病毒猖獗與實作](https://www.youtube.com/watch?v=4F9YUBUSxV8)

## Feature
一個以CSharp實作簡單模擬勒索軟體（基於Windows），提供了範例實作：

* AES加密、解密文件
* 開機自啟動
* RSA加密、解密對稱金鑰
* 隨機化加密文件之檔名（恢復時可正確還原成正確檔名）


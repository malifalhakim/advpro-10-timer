### 1.2 Understanding how it works

![alt text](1-2.png)
Berdasarkan output diatas, terlihat bahwa output "hey hey" diprint terlebih dahulu. Hal ini dikarenakan output "howdy" dan "done" berada di dalam *asynchronus function*. Dimana fungsi asinkronus berjalan di luar fungsi main yang menjalankannya. Karena hal tersebut, "hey hey" diprint terlebih dahulu karena fungsi main akan terus menjalankan programnya. Sementara itu, fungsi asinkronus masih menuggu hasil dari future.


UI檔案存在google雲端中，下載連結如下：
https://drive.google.com/file/d/1e2J_3KMxQYu47Sn1x-qQrWz53ZqvB2dr/view?usp=sharing

使用UI_Windows說明

先點選匯入圖片，再輸入打算執行的轉換的參數，在欄中輸入完參數後，即可點選想要進行的轉換鈕，
其中參數填寫方式如下：

log：c (ex 42)

gamma：r (ex 1.2)

negative：空

Bilinear：h, w (ex 128,128 )

Nearest：h, w (ex 128,128 )

GaussianBlur：kernel size, sigema (ex 3 , 1.5)，kernel size please add odd number

Averaging Filter：kernel size (ex 5)，kernel size choose：3,5,7

Laplacian Filter：kernel size (ex 5)，kernel size choose：3,5,7

Sobel Filter：kernel size (ex 5)，kernel size choose：3,5,7

statistic order filter：kernel size, method (ex 5, 'min')，method choose：'median','min','max'

Bilateral filter：sigma_c, sigma_s, kernal_size, without_smooth (ex 5, 5, 3, False)

nonLocalMeans Filter： bigWindow, smallWindow, h (ex 20, 5, 14)

nonLocalMeans improve Filter：：bigWindowSize, smallWindowSize, sigma, alpha=0.6 (ex 20,5,0.5,0.6)

Unsharp Maskimg：no

Kernel_1 Filter：no

Kernel_2 Filter：no
# Blur Dataset
## Description
This dataset contains 1050 blurred and sharp images (350 triplets), each image triplet is a set of three photos of the same scene: sharp, defocused-blurred and motion-blurred images.

The dataset was created to validate the blur detection algorithm. The dataset can also be used for testing image deblurring, hovewer, the triplets are not "pixel-to-pixel" images, so, one cannot compare blurred and sharp images on the basis of PSNR or SSIM but sharp images can be used for visual comparison.

## Dataset structure

The dataset contains three folders: sharp, defocused-blurred and motion-blurred images.

The filename structure is as follows: id_device_type.extension where
 - ID - a number from 0 to 349;
 - device - the image capture device;
 - type - one of [S, F, M]. S stands for Sharp image, F - deFocused-blurredimage and M - Motion-blurred image.
          
The dataset contains N devices, these are typically smartphones, but several cameras are also provided.

## Download
Kaggle dataset (images were scaled to 1024 pixels by the widest side): todo

Google drive (source images): todo

## Images samples

## Licence
todo

## How to cite
todo


Данная база представляет собой 1050 изображений (350 троек), каждая тройка изображений - это фото одной и той же сцены: чёткое фото, расфокусированное изображение и смазанное в движении.

База создана для проверки алгоритма детектирования блюра на изображении. Также можно использовать для тестов деблюра изображений, однако, это не пиксель в пиксель изображения, поэтому вы не можете использовать сравнение с помощью psnr, ssim и тд, но можно использовать для визуального анализа.

В базе три папки соответственно с чёткими, расфокусированными и смазанными в движении изображениями.

Структура имени файла следующая: ид_девайс_тип. ID - число от 0 до 349, девайс - устройство, которым сделан снимок, тип - дублирующая информация, одно из трех - S sharp, F defocus, M movement blur.

В базе представлены N устройств, в основном, это смартфоны, но есть и фото с фотоаппаратов

bad_id = [10, 86, 121, 164, 192, 195, 17, 36, 47, 53, 89, 106, 154, 44, 46, 48, 87, 88, 94, 97, 104, 110, 128, 136, 139,
          143, 170, 175, 205, 218, 255, 298, 301, 306, 317, 335, 347, 379, 206, 222, 234, 295, 296, 309]

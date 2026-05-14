# 13-Implementaci-n-de-un-Autoencoder-en-una-Red-Denoising-usando-el-dataset-MNIST-
Un Autoencoder Denoising es una red neuronal no supervisada que aprende a eliminar ruido de imágenes. La red recibe una imagen corrompida con ruido  y aprende a reconstruir la imagen **limpia original**, forzándose a aprender únicamente las características estructurales relevantes del dato.

Este proyecto aplica ese principio sobre el dataset **MNIST** (dígitos manuscritos del 0 al 9), demostrando conceptos fundamentales de aprendizaje no supervisado:

- Representaciones comprimidas en un espacio latente
- Arquitectura Encoder–Decoder
- Regularización implícita mediante adición de ruido
- Evaluación con métricas de calidad de imagen: **MSE**, **PSNR** y **SSIM**

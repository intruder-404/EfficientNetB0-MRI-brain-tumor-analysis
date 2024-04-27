
# MRI pituitary- Abnorm(s)



I analyze brain MRI scans from kaggle--datasets(~97% accuracy on evaluation)

Simple convolutional net with efficient-net as backbone(least params and inference time in efficient-net family)

*MobileNet performed noticeably worse(or else, it's size and params are half of that of eff-net/ and, inference time)

Minimal(*not freezing deeper layers in backbone could surprisingly have decreased model depth?)


## Meningioma(ex.)

![App Screenshot](https://storage.googleapis.com/kagglesdsdata/datasets/672377/1183165/Testing/meningioma_tumor/image%2810%29.jpg?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=databundle-worker-v2%40kaggle-161607.iam.gserviceaccount.com%2F20240425%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20240425T212601Z&X-Goog-Expires=345600&X-Goog-SignedHeaders=host&X-Goog-Signature=0d777ce68918e40033d74ba7ffafc90a9d7067008ef0bc40e09a99520b029f0725e3520aac875c5ca864f0f564f5cc9d5343f04bfe730ef9475e66f647114c2876447db86877cdecfd399bf501b3765f8318f20fb99d58358225c74388d9ca26dfd354d466b676355b38138c43c1b527b42a39125a12dfd02290163161922f77f4656c331c49fa07616f90f3dd2b61ca22f654192d3b663c95d75e7799bbea652f7e592a365590d90fdc7cdf8991b0f95328097b2fd03736fd701652695e767cfd4623dbe5598f587d3ddca2377fbc20e45f6d316b6af7e1070222404ea77d16546ca6efb3aa81eadf0b526a6a2af21aa2caa543b953234b29fd704ee87df7bc)


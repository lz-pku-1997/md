此代码基于tensorflow2-keras框架，可通过bool型变量快速开/关Tricks  
代码开头部分为使用华为平台获取数据  
获取完数据则导入相关python包  
然后为一件配置区域，拥有大量可以一键配置的Tricks
/*
brightness和saturation开了为0.96785，没开为0.96071
bool_random_flip_left_right=1
bool_random_flip_up_down=1
bool_random_brightness=1
bool_random_contrast=0
bool_random_hue=0
bool_random_saturation=1

bool_rotation_transform=1
cutmix_rate=0.
mixup_rate= 0.5
gridmask_rate = 0.#降了

pre_trained='noisy-student' # None,'imagenet','noisy-student' 
dense_activation='softmax' #'softmax','sigmoid'
bool_lr_scheduler=1       

tta_times=15
cross_validation_folds=0

bool_focal_loss = 0
label_smoothing_rate=0.

bool_pseudo=1
*/

# Knowledge_Distillation_CIFAR-100
Implementation of knowledge distillation using CIFAR-100 dataset.
- teacher model : ResNet-50
- student model : ResNet-18 (modified ver.)

64.85 % accuracy on validation data after 50 epochs training (about 2 hrs).

Without knowledge distillation, the student model showed lower accuracy (58.45 %), with same parameter settings & training epochs.

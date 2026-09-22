# FPGA-accelerate-1D-CNN
FIRST STEP to develop the fpgas
项目名称：
面向涡旋光空间感知的轻量化 1D-CNN FPGA 边缘推理系统

当前已完成：
1. 仿真数据生成和 FFT 特征提取
2. Phase 1 CNN 软件基线
3. FPGA-friendly CNN
4. INT8 权重量化和 ap_fixed 定点化
5. Vitis HLS C/RTL 仿真
6. Vivado IP 集成
7. Zynq-7020 板级部署
8. OLED、UART、LED、BTN 演示

当前限制：
1. 输入仍以仿真/回放数据为主
2. 当前 FPGA 输出主要是 RPM
3. 几何参数多任务输出尚未完全部署
4. FFT 尚未完成实时 PL 加速

下一阶段：
结构化剪枝、QAT、MobileNet-1D、多任务空间参数估计和实时采集闭环

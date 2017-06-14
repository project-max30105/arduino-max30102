
test
- **硬件部分完整教程（包括元件采购）：** [Sparkfun官方关于MAX30105传感器的使用教程（我们目前有30102）](https://learn.sparkfun.com/tutorials/max30105-particle-and-pulse-ox-sensor-hookup-guide)

# 项目规划

## Stage 1 - 传感器可以正常工作并返回所需数据

### 测试本项目中所需的examples

- [ ] heart rate测量
- [ ] oxygen测量

### 驱动传感器工作

- [ ] **硬件部分完整教程（包括元件采购）：** [Sparkfun官方关于MAX30105传感器的使用教程（我们目前有30102）](https://learn.sparkfun.com/tutorials/max30105-particle-and-pulse-ox-sensor-hookup-guide)
- [ ] **开发环境：** [Arduino IDE使用教程](https://www.arduino.cc/en/Guide/Windows)
- [ ] 请仔细阅读官方教程，搞清楚单片机开发的具体流程

### 传感器会返回什么数据

- [ ] 心率数据（含图线）
- [ ] 血氧数据（含图线）
  
### 连接，通电，测试

- [ ] 阅读教程并连接元件（面包板，线缆，锡焊）
- [ ] 编译上传单片机，测试
- [ ] 看到所需的数据/图线
  
## Stage 2 - 处理传感器数据

- [Windows端数据处理和核心功能实现的代码仓库地址](https://github.com/project-max30102/client-win)
# 固件升级说明

## 一，在线升级固件

版本信息页面,点击检查,如果出现可下载固件提醒,可直接下载升级。

## 二，离线升级固件（通过遥控器）

**升级场景**  
1，当升级过程中,通讯中断、点击取消等等原因会导致升级失败，（如果LED灯5闪白灯,或APP语音播报正在升级飞控/IMU,则表示程序需要升级）如果此时不能进行在线更新的需要使用离线升级。  

2，需要升级测试版本固件（未发布的）也需要通过离线方式升级。

**升级方法**  
1，将要升级的固件文件（V9_AG_XXXX.BIN  /  V7_AG_XXX.BIN）放到安卓系统的遥控器/手机 文件管理->download 文件目录下，并将固件名称重命名为下表中的名称，。  

2，再次进到APP版本信息页面，直接点击升级。  

*-注：升级进度百分比增加表示正在升级。百分比卡在0%,说明通讯故障(检查APP与飞控连接，波特率是否为115200)，或飞控有问题。正常升级V7(5分左右),V9(10分左右)-*

**固件重命名规则**  

| **设备固件** | **重命名**                               |
| ------------ | ---------------------------------------- |
| V9-fmu       | V9_AG_FMU.bin                            |
| V9-pmu       | V9_AG_PMU.bin                            |
| V9-radar     | V9_RADAR_MB0.bin 或者 V9_RADAR_MB1.bin   |
| V9-fradar    | V9_FRADAR_MB0.bin 或者 V9_FRADAR_MB1.bin |
| V9-bradar    | V9_BRADAR_MB0.bin 或者 V9_BRADAR_MB1.bin |
| V7-飞控固件  | V7_AG.bin                                |
| V7-IMU固件   | IMU_AG.bin                               |
| V7-防地雷达  | V7_RADAR.bin                             |
| V7-前避障    | V7_FRADAR.bin                            |
| V7-后避障    | V7_BRADAR.bin                            |
| bs-基站      | RTKBS.bin                                |

**固件下载**  
[V9_FMU固件230408](http://download.jiagutech.com/download/V9_AG_FMU_APP_20230408.bin)  
[V9_PMU固件230421](http://download.jiagutech.com/download/V9_AG_PMU_APP_20230421.bin)  
[V7_FMU固件220510](http://download.jiagutech.com/download/V7_AG_FCU_APP_GPS-RTK_20220510_V73.bin)  
[V7_IMU固件220415](http://download.jiagutech.com/download/IMU_V76_AG_220415.bin)  

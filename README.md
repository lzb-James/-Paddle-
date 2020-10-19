# 基于AI深度学习的疫情监测系统
基于PaddlePaddle的口罩检测模块结合GPS模块、蓝牙模块、RFID模块、以及数据分析可视化大屏对来往学校的人员进行高效筛查

## 摘  要
2020年，一场突如其来的新型冠状病毒性肺炎疫情在全国蔓延，新型冠状病毒对人们的工作和生活均造成了严重的影响，各行各业都在做好疫情防控工作，学校在学生体温管理、口罩检测等等面临诸多严峻问题：为做到疫情防控，公共场所人员进出需要做到佩戴口罩与体温检测。传统体温监测通常使用体温计、体温枪等，工作量大、易交叉感染、容易漏测，无法实时了解个人的体温，无法实时监测人员的体温变化。所以如何对大规模人群精准监测、连续监测、远程测温并实现大数据筛检， 成为常态化防疫的新需求、新挑战。传统疫情防控的运营中，人力资源有限，有交叉感染风险。体温为人力检测，会造成大量人力损耗，不满足公共场所高人流量、高并发的精准监测。因此，通过人工智能和智能手环技术实现对疫情期间的实时管理以及实时监控，促进疫情快点结束，促进社会发展，提高社会运作效率，使疫情监控实现科学化、现代化、人工智能化，满足人工智能化的国家发展战略。同时Paddlepaddle可以结合国产芯片以及国产Linux系统，符合国策。
## Key
**关键词：Paddlepaddle、Rraspberry Pi、AI-bigdata、智能手环** 

## 功能设计
()[]
```
  
  人脸识别

基于百度AI模型库paddlehub，有别于传统的人脸识别检测对设备运行性能要求较大，占用较多的空间检测精度受限等问题，其检测更加迅速精

准，对设备算力要求较低，更加容易部署于各种嵌入式平台。
  
  口罩检测

同样是基于百度AI模型库paddlehub，可以实现对于未带口罩人员的检测。检测不通过时汇报警告信息。
  
  体温监测

传统的基于红外识别的体温检测装置，只支持单次记录人员的体温数据，无法做到对其跟踪且无法做到高精度测量体温。所以我们通过蓝牙测温手

环的接触式体温传感器实时检测个人体温变动并保存上传云端。
  
  GPS定位

当出现疑似或确诊病例时，现有手段需要排查人员行程路线并通过走访调查实现。通过智能手环内置的定位模块定位并记录人员出行位置信息，发生

疫情时可以帮助快速定位出行信息并进行人员排查。
  
  RFID检测

通过门禁装置上安装RFID射频读写器，读取手环内部的电子标签的ID信息，进行人员信息识别。人员通过时，安装于手环内的电子标签会自动读取人

员信息并结合蓝牙网关快速实现配对与数据上传与下载。
  
  蓝牙网关

安装于固定的位置，当人员通过时，所有智能手环通过蓝牙网关上报数据。蓝牙网关可通过与上位机相连上传数据，或直接通过4G/WIFI连接云端服务

器上传数据。
    
  FineBI数据分析平台

接收到来自下位机的人体温度，人脸识别信息，RFID标签等信息，心率。对数据存储、实时分析、向客户端更直观的展示对于疫情的可视化大屏

```
## 效果

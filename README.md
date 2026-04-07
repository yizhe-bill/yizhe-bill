# Hi there 👋

我是bill

本科电子信息工程专业🥑 | 嵌入式小白😊 | 开源文化学习者🎨

## 🔧 技术方向
- SoftWare / Driver-devlopment
- C 
- STM32
- Simple PCB
- Control Algorithm

![C](https://img.shields.io/badge/C-Language-blue)
![STM32](https://img.shields.io/badge/STM32-Embedded-green)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-RTOS-orange)

## 📚 当前学习
- [X] RTOS Core 
- [x] c++
- [x] Data Structure

## 📫 联系方式
- Email: zyz.bill@qq.com

---
## 🌳 我的技术栈技能树

```mermaid
graph TB
    Root((嵌入式技能)):::root
    
    %% 核心基础（树干）
    subgraph Core [核心基础]
        C[C语言]:::core
        Algorithm[控制算法]:::core
    end
    
    %% 硬件平台（主枝）
    subgraph Hardware [硬件平台]
        STM32[STM32]:::hardware
        C51[8051]:::hardware
    end
    
    %% 开发技能（枝杈）
    subgraph Skills [开发技能]
        HAL[HAL库]:::skill
        StdLib[标准库]:::skill
        Driver[驱动开发]:::skill
        Framework[前后台]:::skill
        PCB[PCB设计]:::skill
    end
    
    %% 连接关系
    Root --> C
    Root --> Algorithm
    Root --> STM32
    Root --> C51
    
    STM32 --> HAL
    STM32 --> Driver
    C51 --> StdLib
    C51 --> Driver
    
    Driver --> Framework
    C --> PCB
    
    %% 样式定义
    classDef root fill:#4a6fa5,stroke:#1a365d,color:white,stroke-width:2px
    classDef core fill:#4CAF50,stroke:#2E7D32,color:white
    classDef hardware fill:#2196F3,stroke:#0D47A1,color:white
    classDef skill fill:#FF9800,stroke:#E65100,color:white

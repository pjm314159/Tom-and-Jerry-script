# 猫和老鼠手游宏键位
***
## 说明 
所有位置要根据你的键位精细设置，宏对于网络延迟较高，卡的时候慎用。<br>
*#后面为注释,要删掉*
***
## 通用
+ ### 技能 
  + #### 小跳放
    ```
    press 988,362  # 技能位置
    sleep 50
    press 1099,441  # 空格位置
    release 988,362
    release 1099,441
    ```
  + #### 大跳放
    ```
    press 988,362  # 技能位置
    sleep 150
    press 1099,441 # 空格位置
    release 988,362
    release 1099,441
    ```
+ ### 机器鼠
  ```
  press 469,422 # 机器鼠位置
  sleep 150
  press 1099,441 # 空格位置
  release 469,422
  release 1099,441
  ```
+ ### 交互
    + #### 爬梯
        ```
        loop until_release
        press 867,292 1122,442 # 交互键和空格键
        sleep 50
        release 867,292 1122,442
        sleep 30
        loop_end
        ```
    + #### 喝药水 <br>
        与技能相同，把技能位置换成药水位置
        + 大跳
        + 小跳 
    + #### 跳夹<br>
        与技能相同，把技能位置换成药水位置
        + 大跳
        + 小跳 
+ ### 特殊
    + #### 大表哥
        + 升龙拳闪拳
            ```
            click 848,407 # 按完传送，老鼠头像的位置
            sleep 1580
            click 1065,310 # 道具键
            curve 1000,374 997,298 # 拳头的位置
            sleep 280
            click 1072,330 
            ```
        + 游龙拳闪拳
            ```
            click 848,407 # 按完传送，老鼠的位置
            sleep 1580
            click 1065,310  # 道具键
            click 985,372  # 拳头的位置
            sleep 280
            click 1103,311 # 道具键
            ```
        + 踏空
            ```
            click 898,432 # 按完传送，老鼠头像的位置
            sleep 1580
            click 1128,329 # 道具键
            loop 5
            click 1138,471 # 跳跃键
            sleep 2
            loop_end
            loop 15
            click 906,315 # 交互键
            sleep 1
            loop_end
            sleep 600
            loop 30
            click 868,529 # 漂浮键
            sleep 2
            loop_end
            ```
        + 游龙拳
            ```
            click 985,372  # 拳头的位置
            sleep 280
            click 1103,311 # 道具键
            ```
    + #### 凯特
        + 无后摇舔狗
            ```
            click 983,479 # 一技能
            sleep 600
            click 1052,321 # 道具键
            ``` 
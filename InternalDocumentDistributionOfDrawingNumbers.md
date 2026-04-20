1. 目的和范围

本指南定义了SYS系统工程部图纸编号的规则。本指南对项目工程师具有约束力（电气可参考）。

2. 机械制图命名法
易搜索
可重复多次利用
交流方便
版本控制

 - 总图
    - SYSW**XXAAA-000-TT**
    - XX:项目年度
    - AAA：项目号
    - TT: 版本index
         00              第0版(可省略)
         01              第1版(不可省略 )
         02              第2版(不可省略 )
         Etc
    - **示例** SYSW19025-01 SYSW19025项目总图第1版

 - 子装配
    - 0XX-AAA-0BB-TT**AsmYYY**
    - XX:项目年度
    - AAA：项目号
    - 0BB: 子装配系列号
         081              第1子装配
         082              第2子装配
         083              第3子装配
         Etc
    - TT: 版本index
         00              第0版(可省略)
         01              第1版(不可省略 )
         02              第2版(不可省略 )
         Etc         
    - AsmYYY: 按功能自定义（用英文，例如：AsmFrame, AsmFixture, ...[驼峰命名法](https://baike.baidu.com/item/%E9%AA%86%E9%A9%BC%E5%91%BD%E5%90%8D%E6%B3%95?fr=aladdin)）       
    - 示例 019-025-081AsmWeldingUnit(SYSW19025项目焊接单元模组装配图)

 - 零件图
    - 0XX-AAA-BBB-TTYYY
    - XX:项目年度
    - AAA：项目号
    - BBB: 子装配系列号
         001              
         002              
         ...
         080              
         Etc
    - TT: 版本index
         00              第0版(可省略)
         01              第1版(不可省略 )
         02              第2版(不可省略 )
         Etc         
    - YYY: 按功能自定义（用英文，例如：Bracket, BasePlate, Stopper...[驼峰命名法](https://baike.baidu.com/item/%E9%AA%86%E9%A9%BC%E5%91%BD%E5%90%8D%E6%B3%95?fr=aladdin)）       
    - 示例 019-025-011AdjustPlate(SYSW19025项目调整板)

 - 标准件
     - XXX-AAA-BBB**YYYZZZ**
     - XXX-AAA-BBB:Item_Master所列EDP码
     - YYYZZZ：供应商及型号信息（SMCCylinderMKB40-20LZ-M9BL,FestoCylinerDFM-20-50-P-A-GF...）
     - 注意标准件是零件，非部件，通过布置控制不同的形态。
     - 没有EDP的标准件采用**899-001-058**
     - 示例：839-005-999MisumiSHFZ30-30米思米衬套

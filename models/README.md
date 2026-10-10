# GMS / SEEP2D models

[Project](../README.md) · [中文说明](../README.zh-CN.md)

- [without-clay.zip](without-clay.zip): baseline cofferdam.
- [with-clay.zip](with-clay.zip): cofferdam with a 25 m clay blanket.
- [manifest.json](manifest.json): archive member paths, byte sizes and SHA-256 hashes.

Extract each ZIP to a separate folder and retain its subfolder structure. Open the `.gpr` project in GMS with SEEP2D support; the analysis used GMS 10.5. Keep the companion SEEP2D files beside the project in their archived locations. Check units and the 18 m / 12 m head boundaries before running or changing the model.

The archives preserve the model inputs and available solver outputs. They have been checked for archive integrity; the solver has not been rerun during preparation of this repository.

中文：分别解压两个方案，保留文件夹层级，在支持 SEEP2D 的 GMS 中打开 `.gpr`。运行前检查单位、水头边界和输出路径。原分析使用 GMS 10.5；本次整理保留原工程与已有输出。

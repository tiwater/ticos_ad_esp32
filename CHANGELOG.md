esp32、esp32s3和esp32c3替换掉库libfatfs.a, 使支持中文文件名和长文件名。
编译时配置选项如下：
CONFIG_FATFS_CODEPAGE_936=y
CONFIG_FATFS_LFN_STACK=y
CONFIG_FATFS_MAX_LFN=255
CONFIG_FATFS_API_ENCODING_UTF_8=y
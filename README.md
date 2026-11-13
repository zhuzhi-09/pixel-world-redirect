# Pixel World 旧域名跳转

`pcl.pw.zhuzhi.site` 的 GitHub Pages 跳转页，访问后会把路径、查询参数和锚点带到 `https://pixelworld.zhuzhi.site`。

这个仓库只负责跳转，不包含启动器代码。

旧版本启动器只会请求 `pcl.pw.zhuzhi.site/api/v1/update.json`，所以这里保留一份更新接口。`.github/workflows/sync-api.yml` 每 10 分钟从主仓库的 site 分支同步一次，不需要手动更新。

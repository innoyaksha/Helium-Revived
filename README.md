<br />
<p align="center">

  <h2 align="center" style="font-weight: 600">Helium Music Revived</h2>

  <p align="center">
    ⚠️请注意：本项目是已经被删库的 <a href="https://github.com/Kaidesuyo/Hydrogen-Music" target="_blank">Hydrogen-Music</a> 的分支。
    <br />
    因NE增加了云盾验证，密码登录可能无法使用，请使用二维码登录。
    <br />
    请尽量不要使用云盘中的上传功能，目前上传失败概率大且内存无法得到释放。
    <br />
    欢迎各位前往本仓库继续维护这个分支。
    <br />
    注：此项目目前由Yaksha Arkinova Innovations复刻后通过Google Firebase Studio开始维护。因此其commit信息作者系Google平台用户。
    <br />
    因此将会在 <a href="https://github.com/innoyaksha" target="_blank">Yaksha Innovations GitHub组织</a> 进行软件的LTS更新支持。
    <br />
    <a href="#%EF%B8%8F-安装" target="blank"><strong>📦️ 下载安装包</strong></a>
    <br />
    <br />
  </p>
</p>

## 📦️ 安装

访问 [Releases](https://github.com/mtr-static-official/Helium-Music/releases)
页面下载安装包。

注：0.4.1版本正在开发中，故暂时链接至upstream的release

## 👷‍♂️ 打包客户端

~~由于个人设备限制，只打包了Windows平台的安装包且并未适配macOs与Linux平台。~~
本分支此前完成了Windows平台和Linux平台的打包，macOS由于个人设备限制暂未打包。
如有可能，您可以在开发环境中自行适配。

```shell
# 打包
npm run dist
```

## :computer: 配置开发环境

运行本项目

```shell
# 安装依赖
npm install

# 运行Vue服务
npm run dev

# 运行Electron客户端
npm start
```

## 📜 开源许可

本项目仅供个人学习研究使用，禁止用于商业及非法用途。

基于 [MIT license](https://opensource.org/licenses/MIT) 许可进行开源。

## 灵感来源

基于Hydrogen Music修改而来，感谢[Hydrogen-Music](https://github.com/Kaidesuyo/Hydrogen-Music)。

感谢[Google Firebase Studio](https://firebase.studio)对云开发环境的环境支持。

## 🖼️ 截图

![home][home-screenshot]
![playlist][playlist-screenshot]
![lyric][lyric-screenshot]
![music_video][music_video-screenshot]

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[home-screenshot]: img/home.png
[playlist-screenshot]: img/playlist.png
[lyric-screenshot]: img/lyric.png
[music_video-screenshot]: img/music_video.png

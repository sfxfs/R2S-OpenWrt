# NanoPi-R2S 的 OpenWrt 固件  
**R2S-OpenWrt-Original**: 基于 [nicksun98/R2S-OpenWrt](https://github.com/nicksun98/R2S-OpenWrt) 对 [openwrt/openwrt](https://github.com/openwrt/openwrt) 进行定制编译  
**R2S-OpenWrt-Lean**: 对 [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede) 进行定制编译  

## 固件特性  
1. 设置主机名为 `NanoPi-R2S`  
2. 默认 LAN IP： `192.168.1.1`  
3. 默认用户、密码： `root` `无`  
4. 插件仅包含： `OpenClash` `SSRPlus` `Samba4网络共享`  
5. 重命名 `ShadowSocksR Plus+` 为 `SSRPlus`，并微调其设置首页内容  
6. 主题仅包含 `luci-theme-argon` 且删除主题底部文字  
7. R2S-OpenWrt-Original 精简 LuCI 界面，移除 `备份/升级`  
8. R2S-OpenWrt-Lean 精简 LuCI 界面，移除 `软件包` `挂载点` `备份/升级`  
9. R2S-OpenWrt-Original 移除上游的 `fuck` 组件  
10. 默认关闭 `IPv6`  

## 感谢  
   感谢所有提供了上游项目代码和给予了帮助的大佬们  

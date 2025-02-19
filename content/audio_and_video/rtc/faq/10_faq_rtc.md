---
title: "常见问题"
draft: false
collapsible: false
weight: 10
---

## 为什么开启云录制前必须开启对象存储？

云录制为将需要录制的视频进行合流，最终形成一个视频文件，对象存储用以存储该录制完成的视频文件。

## 录制的视频如何播放？

录制完成的视频您可以在对象存储控制台进行查看。若需要大规模不受限制播放，可以将青云 CDN 或第三方 CDN 的回源地址配置为对象存储地址。

## 资源套餐包过期，资源分钟数还可以使用么？

不可以。

## 购买多个套餐包，如何扣除？

系统会优先扣除您领取的免费资源分钟数，然后根据您购买的套餐包有效期，优先扣除将要失效的套餐包资源分钟数。

## 为什么会有音频分钟数消耗？

当频道里只有一个人时，实时音视频 RTC 统计通话分钟数时，仅统计为音频分钟数。

当多余一个人在频道中，且有视频流发送和接收时，实时音视频 RTC 才统计为视频通话分钟数，且仅统计为视频通话分钟数。

## 为什么生成的临时 Token 有效期只有 24 小时？

临时 Token 用于应用调试使用，不建议用于真实业务。

## 用量展示延迟多久？

不晚于次日 1 点展示当日用量。

## 关于免费资源分钟说明？

- 若购买套餐包，则优先扣除免费资源分钟。
- 免费分钟自领取成功后开始计算有效期。
- 新手 demo 体验与测试，均会优先扣除免费资源分钟数，然后扣除已购买资源分钟数。
- 免费资源分钟扣除计算规则与付费套餐规则一致。

## 购买的套餐包如何退订？

购买的套餐包不支持退订，仅支持在有效期内进行使用。


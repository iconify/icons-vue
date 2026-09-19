<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5h-1f8sa"/><circle class="sbotpimww"/><circle class="zq5pzrboi"/><circle class="f0yc0y7ny"/><path class="q-udmo56r"/><path class="mcw_6abxx"/><circle class="yjqeqfbjr"/><circle class="rfgv0sb9j"/><circle class="oclompb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-bathroom" /></template>
<style>
.f0yc0y7ny {
  cx: 15px;
  cy: 17px;
  r: 1px;
  fill: currentColor;
}

.mcw_6abxx {
  fill: currentColor;
  d: path("M17 11c0-2.76-2.24-5-5-5s-5 2.24-5 5v1h10zm-8.46-.5c.24-1.69 1.7-3 3.46-3s3.22 1.31 3.47 3z");
}

.oclompb7u {
  cx: 12px;
  cy: 17px;
  r: 1px;
  fill: currentColor;
}

.q-udmo56r {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 18H4V4h16z");
}

.rfgv0sb9j {
  cx: 9px;
  cy: 14px;
  r: 1px;
  fill: currentColor;
}

.sbotpimww {
  cx: 15px;
  cy: 14px;
  r: 1px;
  fill: currentColor;
}

.t5h-1f8sa {
  fill: currentColor;
  d: path("M4 20h16V4H4zm5-2c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m0-3c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m3 3c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m0-3c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m3 3c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m0-3c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m-8-4c0-2.76 2.24-5 5-5s5 2.24 5 5v1H7z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.yjqeqfbjr {
  cx: 9px;
  cy: 17px;
  r: 1px;
  fill: currentColor;
}

.zq5pzrboi {
  cx: 12px;
  cy: 14px;
  r: 1px;
  fill: currentColor;
}

</style>

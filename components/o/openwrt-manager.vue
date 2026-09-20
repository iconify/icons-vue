<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vkxu0rbou"/><path class="v8uuzpbfi"/><circle class="arz5y4bcu"/><path class="lzyicmd5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openwrt-manager" /></template>
<style>
.arz5y4bcu {
  cx: 23.33px;
  cy: 24.525px;
  r: 2.635px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lzyicmd5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.457 38.13q.038-.29.04-.582a5 5 0 0 0-.04-.58l1.258-.986a.29.29 0 0 0 .073-.38l-1.191-2.067a.29.29 0 0 0-.364-.128l-1.485.599a4.6 4.6 0 0 0-1.005-.581l-.224-1.578a.29.29 0 0 0-.29-.25h-2.39a.29.29 0 0 0-.29.25l-.224 1.578a4.5 4.5 0 0 0-1.005.58l-1.491-.598a.29.29 0 0 0-.363.128L31.274 35.6a.29.29 0 0 0 .073.38l1.255.986a5 5 0 0 0-.04.581q.002.293.04.581l-1.255.986a.29.29 0 0 0-.073.38l1.192 2.067a.29.29 0 0 0 .363.128l1.485-.6c.309.237.647.432 1.005.582l.224 1.578a.29.29 0 0 0 .29.25h2.384a.29.29 0 0 0 .29-.25l.224-1.578q.541-.225 1.006-.581l1.485.599a.29.29 0 0 0 .363-.128l1.192-2.067a.29.29 0 0 0-.073-.38zm-4.426 1.505a2.087 2.087 0 1 1 2.084-2.09v.003a2.084 2.084 0 0 1-2.08 2.087z");
}

.v8uuzpbfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.17 10.365c7.82-7.82 20.5-7.82 28.32 0");
}

.vkxu0rbou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.642 14.836c5.35-5.35 14.026-5.35 19.377 0M30.18 36.39a13.701 13.701 0 0 1-18.715-18.715m23.731-.001a13.7 13.7 0 0 1 .792 12.094m-17.875-10.46a7.38 7.38 0 0 1 10.434 0");
}

</style>

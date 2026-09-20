<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hzbhvwzxd"/><path class="bgmcrbcdd"/><path class="zh6-txvmz"/><path class="sfjortb-o"/><path class="iuwfsxlzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trowel-duotone-bold" /></template>
<style>
.bgmcrbcdd {
  fill: currentColor;
  d: path("M10 4h4v3h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hzbhvwzxd {
  fill: currentColor;
  d: path("M7 12h10c0 4 -3 7 -5 9 -2 -2 -5 -5 -5 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iuwfsxlzr {
  d: path("M10 4h4v3h-4Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sfjortb-o {
  d: path("M12 7v5");
}

.zh6-txvmz {
  d: path("M7 12h10c0 4 -3 7 -5 9 -2 -2 -5 -5 -5 -9");
}

</style>

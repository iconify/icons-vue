<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxow7abeb"/><path class="abnm6smsv"/><path class="mfc7nxp-y"/><path class="br5oj-bon"/><path class="n6bbuubnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:priority-class-duotone-bold" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.br5oj-bon {
  d: path("m10 13 2 -2 2 2");
}

.mfc7nxp-y {
  d: path("M9 7h6");
}

.n6bbuubnx {
  d: path("m10 16 2 -2 2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yxow7abeb {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

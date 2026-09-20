<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxow7abeb"/><path class="abnm6smsv"/><path class="pty_wsbvs"/><path class="gcalxb98a"/><path class="qtxvlht3c"/><path class="ozrmsubaj"/><path class="r2fb1fafl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sentence-window-duotone-bold" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.gcalxb98a {
  d: path("M8 13h8");
}

.ozrmsubaj {
  d: path("M9.5 11v4");
}

.pty_wsbvs {
  d: path("M8 9h8");
}

.qtxvlht3c {
  d: path("M8 17h8");
}

.r2fb1fafl {
  d: path("M14.5 11v4");
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

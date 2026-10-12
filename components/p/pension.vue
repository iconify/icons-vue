<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="evhw-ccjv"/><path class="u7n8e3bvt"/><circle class="ygphxfbhc"/><path class="s8b530p9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pension" /></template>
<style>
.evhw-ccjv {
  d: path("M18.25 10.32a7.75 7.75 0 1 0-7.93 7.93a7 7 0 0 1 7.93-7.93");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s8b530p9p {
  d: path("M18.38 16.27c-.21-.45-.62-.75-1.12-.75c-.67 0-1.17.39-1.17.86c0 1.22 2.34.61 2.34 1.78c0 .49-.5.83-1.17.83c-.52 0-.96-.28-1.14-.73");
}

.u7n8e3bvt {
  d: path("M10.5 6.25v4.25H7");
}

.ygphxfbhc {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
}

</style>

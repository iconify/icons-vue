<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="xkqyiwblc"/><ellipse class="qhsg76bkh"/><path class="wbod-obam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-heart-rounded-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qhsg76bkh {
  cx: 9px;
  cy: 17px;
  opacity: var(--svg-opacity--0-5, 0.5);
  rx: 7px;
  ry: 4px;
}

.wbod-obam {
  stroke-linejoin: round;
  d: path("M17.0885 12.5385C16.2058 11.8648 15 11.1121 15 9.69973C15 8.28732 16.65 7.28567 18 8.64354C19.35 7.28567 21 8.28732 21 9.69973C21 11.1121 19.7942 11.8648 18.9115 12.5385C18.6 12.7762 18.3 13 18 13C17.7 13 17.4 12.7762 17.0885 12.5385Z");
}

.xkqyiwblc {
  cx: 9px;
  cy: 6px;
  r: 4px;
}

</style>

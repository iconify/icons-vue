<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="jw8tf-_cs"/><circle class="tyzpclblr"/><path class="tffx2vbbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pollen" /></template>
<style>
.jw8tf-_cs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.16 12.37A2.25 2.25 0 1 1 12.34 16a2.25 2.25 0 1 1-3.09 2.25A2.25 2.25 0 1 1 6.16 16a2.25 2.25 0 1 1 1.18-3.63a2.25 2.25 0 1 1 3.82 0");
}

.tffx2vbbs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 9h.01m-.76-4.75h.01M20 5.5h.01");
}

.tyzpclblr {
  cx: 9.25px;
  cy: 15px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

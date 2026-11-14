<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xy3juubbx"/><path class="mdoawy4yh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:template-literal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mdoawy4yh {
  d: path("M10.25 11.75c-1 0-1.25.5-1.25 1.25v1c0 .6-.4 1-1 1c.6 0 1 .4 1 1v1c0 .75.25 1.25 1.25 1.25m3.5-6.5c1 0 1.25.5 1.25 1.25v1c0 .6.4 1 1 1c-.6 0-1 .4-1 1v1c0 .75-.25 1.25-1.25 1.25");
}

.xy3juubbx {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5m.375 2.75l1.5 3m2-3l1.5 3");
}

</style>

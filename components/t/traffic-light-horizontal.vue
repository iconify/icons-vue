<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eez2fccme"/><path class="k9fhdnbwh"/><path class="pt7kblb5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:traffic-light-horizontal" /></template>
<style>
.eez2fccme {
  d: path("M6.5 7.5h11A4.5 4.5 0 0 1 22 12a4.5 4.5 0 0 1-4.5 4.5h-11A4.5 4.5 0 0 1 2 12a4.5 4.5 0 0 1 4.5-4.5m5.5 0V3M9 3h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k9fhdnbwh {
  fill: currentColor;
  d: path("M4.75 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.pt7kblb5y {
  d: path("M10.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m5.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>

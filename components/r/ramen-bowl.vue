<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gc99geuhv"/><path class="cfhrd-b1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ramen-bowl" /></template>
<style>
.cfhrd-b1h {
  d: path("M6.75 15.5q1.5 1.2 3 0c1.5-1.2 2-.8 3 0s2 .8 3 0s2 .8 3 0");
}

.gc99geuhv {
  d: path("M3.75 12h16.5a.75.75 0 0 1 .75.85a9 7.5 0 0 1-18 0a.75.75 0 0 1 .75-.85m.75-9L8 12m0-9.25L10.25 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

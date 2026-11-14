<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wqhu2jbtv"/><path class="wvlr2oyce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mulch-bag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wqhu2jbtv {
  d: path("M8.5 7c-4.5 2.5-5 10-4 12A1.5 1.5 0 0 0 6 21h12a1.5 1.5 0 0 0 1.5-2c1-2 .5-9.5-4-12Zm0 0l-2-4h11l-2 4");
}

.wvlr2oyce {
  d: path("M9 17q0-5.5 6-5.5Q15 17 9 17");
}

</style>

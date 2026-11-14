<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v4wzdtb_w"/><path class="wye801-xo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:succulent" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v4wzdtb_w {
  d: path("M8.652 15h6.696a1.75 1.75 0 0 1 1.713 2.107l-.521 2.5A1.75 1.75 0 0 1 14.827 21H9.173a1.75 1.75 0 0 1-1.713-1.393l-.521-2.5A1.75 1.75 0 0 1 8.652 15M12 15c-2-3-2-8.5 0-12c2 3.5 2 9 0 12");
}

.wye801-xo {
  d: path("M12 15c-4 0-7-3-8-6.5c3.75.5 6.5 2.5 8 6.5m0 0c4 0 7-3 8-6.5c-3.75.5-6.5 2.5-8 6.5");
}

</style>

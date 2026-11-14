<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dqdx4r2ft"/><path class="knapdbc1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:refrigeration-cycle" /></template>
<style>
.dqdx4r2ft {
  d: path("M9.25 4h5.5A5.25 5.25 0 0 1 20 9.25v5.5A5.25 5.25 0 0 1 14.75 20h-5.5A5.25 5.25 0 0 1 4 14.75v-5.5A5.25 5.25 0 0 1 9.25 4M12 8.5v7m-3-5.25l6 3.5m-6 0l6-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knapdbc1i {
  d: path("M11 2.25L12.75 4L11 5.75m2 12.5L11.25 20L13 21.75");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ewjjxtbgh"/><path class="n3zrl5mfv"/><path class="r-6mznbnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:paw-balm" /></template>
<style>
.ewjjxtbgh {
  d: path("M2.5 10a9.5 7.5 0 1 0 19 0a9.5 7.5 0 1 0-19 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n3zrl5mfv {
  d: path("M2.5 10v3.5a9.5 7.5 0 0 0 19 0V10");
}

.r-6mznbnk {
  d: path("M9 12.75a3 2.25 0 1 0 6 0a3 2.25 0 1 0-6 0m-1-4h.01m3.99-2h.01m3.99 2h.01");
}

</style>

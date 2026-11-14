<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="su75vcb-l"/><path class="f_a3m_bgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sleep-cycle" /></template>
<style>
.f_a3m_bgc {
  d: path("M21 6h-3v3m-4-.5a4.5 4.5 0 1 0 1.5 6.5A3.75 3.75 0 0 1 14 8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.su75vcb-l {
  d: path("M12 3.5A8.5 8.5 0 1 0 18 6");
}

</style>

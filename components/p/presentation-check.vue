<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pmxb66bct"/><path class="n85k5jbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:presentation-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n85k5jbrp {
  d: path("M8.5 9.5L11 12l4.5-4.5");
}

.pmxb66bct {
  d: path("M2.5 3.5h19M4 3.5V14a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V3.5M8 21l2-5m6 5l-2-5");
}

</style>

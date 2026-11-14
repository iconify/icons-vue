<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tu3o_tbfa"/><path class="ldhiy1bbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:waterfront-property" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldhiy1bbe {
  d: path("M10.5 13.5v-3h3v3M3 17q1.5-1.25 3 0t3 0t3 0t3 0t3 0t3 0M3 20.5q1.5-1.25 3 0t3 0t3 0t3 0t3 0t3 0");
}

.tu3o_tbfa {
  d: path("m6.439 8.561l4.5-4.5a1.5 1.5 0 0 1 2.122 0l4.5 4.5A1.5 1.5 0 0 1 18 9.621V12a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 12V9.621a1.5 1.5 0 0 1 .439-1.06M2.5 13.5h19");
}

</style>

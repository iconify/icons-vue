<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c81k7vb4q"/><path class="wz6_99bsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:presentation-board" /></template>
<style>
.c81k7vb4q {
  d: path("M5.625 3h12.75A2.625 2.625 0 0 1 21 5.625v6.75A2.625 2.625 0 0 1 18.375 15H5.625A2.625 2.625 0 0 1 3 12.375v-6.75A2.625 2.625 0 0 1 5.625 3M8 15l-2 6.5M16 15l2 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wz6_99bsl {
  d: path("m6.5 11.5l3.5-3l3 1.5l4.5-4");
}

</style>

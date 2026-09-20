<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ppbx_abyw"/><path class="x3jvrbc_p"/><path class="wike1pbjp"/><path class="glqgnwb4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stranger-outline-thin" /></template>
<style>
.glqgnwb4y {
  d: path("M17.5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ppbx_abyw {
  d: path("M6 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.wike1pbjp {
  d: path("M17 7c0 -2 3 -2 3 0s-1.5 2 -1.5 4");
}

.x3jvrbc_p {
  d: path("M5 17a4 4 0 0 1 8 0");
}

</style>

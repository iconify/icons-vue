<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hg6_dnbgv"/><path class="qvj567l4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:store-walk" /></template>
<style>
.hg6_dnbgv {
  d: path("M11.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m1 3.5l-2 6l3 3V21m-3-7.5l-2 4l-2.5 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qvj567l4l {
  d: path("m7.5 11l4-3l4 3.5M18 9h2.5M18 12h2.5");
}

</style>

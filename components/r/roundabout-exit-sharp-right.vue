<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c82l2lwth"/><path class="htnno_n8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:roundabout-exit-sharp-right" /></template>
<style>
.c82l2lwth {
  d: path("M10.75 21.5v-7a5 5 0 0 0 3.5-1.5l4 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.htnno_n8l {
  d: path("M15 17h3.25v-3.25m-7.5.75a5 5 0 1 1 5-4.25");
}

</style>

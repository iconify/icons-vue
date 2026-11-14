<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lmyenyd6r"/><path class="rwdjljwek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wonky-veg" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lmyenyd6r {
  d: path("M4.5 9.5c0-3.5 4-5 6-3l6 7c1 1.5 1 4 4 6.5c-4 0-6-2.5-7-3.5l-8-5c-.5-.5-1-1-1-2");
}

.rwdjljwek {
  d: path("m6 2.5l.25 3.75l-3.5-1");
}

</style>

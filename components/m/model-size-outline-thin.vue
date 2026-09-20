<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i3nsbzblu"/><path class="rg7tj2b_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-size-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i3nsbzblu {
  d: path("m10 3 7 7 -7 7 -7 -7Z");
}

.rg7tj2b_x {
  d: path("m18 14 3.5 3.5L18 21l-3.5 -3.5Z");
}

</style>

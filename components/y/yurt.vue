<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="adc5w46wu"/><path class="xqrf9bb2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:yurt" /></template>
<style>
.adc5w46wu {
  d: path("M3.5 20.5V13c0-5 4-7.5 8.5-7.5S20.5 8 20.5 13v7.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xqrf9bb2q {
  d: path("M9.5 20.5V15h5v5.5M12 5.5V3");
}

</style>

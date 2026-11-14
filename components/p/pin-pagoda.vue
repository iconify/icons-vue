<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x4t41n83s"/><path class="wyli5loxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-pagoda" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wyli5loxo {
  d: path("M10.5 21.5v-3h3v3");
}

.x4t41n83s {
  d: path("M12 2.5v2M5 9q4.5-1 7-4.5Q14.5 8 19 9Zm3.5 0v3.5m7-3.5v3.5M3 15.5q4.5-.5 5.5-3h7q1 2.5 5.5 3Zm3 0v6h12v-6");
}

</style>

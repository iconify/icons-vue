<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g9oh42b2z"/><path class="n4_c2bb2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:twofa-hardware-key" /></template>
<style>
.g9oh42b2z {
  d: path("M6.5 8.5h4A3.5 3.5 0 0 1 14 12a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 3 12a3.5 3.5 0 0 1 3.5-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n4_c2bb2r {
  d: path("M5.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.5 0h7m-3 0v3");
}

</style>

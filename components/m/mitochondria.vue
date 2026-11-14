<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p-garlb4d"/><path class="odu_9qkoh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mitochondria" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.odu_9qkoh {
  d: path("m5.25 14l3-5l3 6l3-6l3 6l1.5-3");
}

.p-garlb4d {
  d: path("M2.5 12c0-3.5 4.25-6.5 9.5-6.5s9.5 3 9.5 6.5s-4.25 6.5-9.5 6.5s-9.5-3-9.5-6.5");
}

</style>

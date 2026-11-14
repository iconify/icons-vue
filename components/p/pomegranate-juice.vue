<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z4hjcppvi"/><path class="goxf-3b_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pomegranate-juice" /></template>
<style>
.goxf-3b_m {
  d: path("M16.75 15.75V14L18 15l1.25-1v1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z4hjcppvi {
  d: path("M4.581 2.5h6.338a1.5 1.5 0 0 1 1.498 1.579l-.842 16a1.5 1.5 0 0 1-1.498 1.421H5.423a1.5 1.5 0 0 1-1.498-1.421l-.842-16A1.5 1.5 0 0 1 4.581 2.5M3.25 6h9M15 18.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>

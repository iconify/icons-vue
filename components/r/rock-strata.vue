<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l1u6m9bnu"/><path class="dp67lo3zq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rock-strata" /></template>
<style>
.dp67lo3zq {
  d: path("m9.5 6.75l2 5.25l-3.25 3.25M11.5 12l5.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l1u6m9bnu {
  d: path("m3.14 18.04l1.22-5.33Q4.75 11 5.99 9.76l2.27-2.27q1.24-1.24 2.98-1.03l2.77.33q1.74.21 2.94 1.48l2.1 2.21q1.2 1.27 1.42 3.01l.56 4.52q.22 1.74-1.53 1.74h-15q-1.75 0-1.36-1.71");
}

</style>

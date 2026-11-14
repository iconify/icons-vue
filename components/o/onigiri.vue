<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rqsy0jx5l"/><path class="z-f0_ttsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:onigiri" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rqsy0jx5l {
  d: path("m15.051 8.923l3.015 5.361a3.5 3.5 0 0 1-3.05 5.216H8.984a3.5 3.5 0 0 1-3.05-5.216l3.015-5.361a3.5 3.5 0 0 1 6.102 0");
}

.z-f0_ttsg {
  d: path("M10 13.5h4a1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 18v-3a1.5 1.5 0 0 1 1.5-1.5");
}

</style>

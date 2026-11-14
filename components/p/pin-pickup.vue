<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="avgtq2bva"/><path class="r0cgiyb_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-pickup" /></template>
<style>
.avgtq2bva {
  d: path("M9.75 3h6.5A1.75 1.75 0 0 1 18 4.75v5a1.75 1.75 0 0 1-1.75 1.75h-6.5A1.75 1.75 0 0 1 8 9.75v-5A1.75 1.75 0 0 1 9.75 3M2.5 14.5h4c1.5 0 2.5 1 4 1h3a1.5 1.5 0 0 1 0 3H10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r0cgiyb_v {
  d: path("m13.5 18.5l5.25-2.5a1.6 1.6 0 0 1 2 2.5l-5.75 3H2.5M13 3v3.5");
}

</style>

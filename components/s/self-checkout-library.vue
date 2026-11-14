<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z-drco9lt"/><path class="ohh13ab8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:self-checkout-library" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ohh13ab8y {
  d: path("M7.5 16a2.5 2.5 0 0 1 2.5-2.5h6.5M2.5 7V5A2.5 2.5 0 0 1 5 2.5h2m10 0h2A2.5 2.5 0 0 1 21.5 5v2m0 10v2a2.5 2.5 0 0 1-2.5 2.5h-2m-10 0H5A2.5 2.5 0 0 1 2.5 19v-2m2-7h15");
}

.z-drco9lt {
  d: path("M7.5 16V8A2.5 2.5 0 0 1 10 5.5h6.5v13H10A2.5 2.5 0 0 1 7.5 16");
}

</style>

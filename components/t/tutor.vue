<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="vkh2p_buw"/><path class="y_f3o1p3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tutor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vkh2p_buw {
  cx: 7.5px;
  cy: 7px;
  r: 2.75px;
}

.y_f3o1p3c {
  d: path("M3.75 21.25v-4.5a3.75 3.75 0 0 1 7.5 0v4.5Zm10.25-10c1.4-.6 2.6-.5 3.5.35c.9-.85 2.1-.95 3.5-.35v7c-1.4-.6-2.6-.5-3.5.35c-.9-.85-2.1-.95-3.5-.35Zm3.5.35v7");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nnzlfsekh"/><path class="teszqoqtj"/><path class="zqsgc7abe"/><path class="rcqkqehsw"/><path class="atlx6nxij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:metered-billing-outline-thin" /></template>
<style>
.atlx6nxij {
  d: path("m12 13.5 2.5 -2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nnzlfsekh {
  d: path("M2 8a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.rcqkqehsw {
  d: path("M8.71 12.3a3.5 3.5 0 0 1 6.58 0");
}

.teszqoqtj {
  d: path("M5.5 10.5v3");
}

.zqsgc7abe {
  d: path("M18.5 10.5v3");
}

</style>

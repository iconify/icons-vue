<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oaf0dvc-u"/><path class="y9anvskex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:power-cycle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oaf0dvc-u {
  d: path("M16 6a8 8 0 1 1-8 0m4-3.5V11");
}

.y9anvskex {
  d: path("M5 5.25L8 6l-.75 3");
}

</style>

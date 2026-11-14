<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f8w58tb4x"/><path class="nc0vl2seq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:solar-car" /></template>
<style>
.f8w58tb4x {
  d: path("M5 18H2.5v-3.5A1.5 1.5 0 0 1 4 13h2.5L9 9.5h6l2.5 3.5H20a1.5 1.5 0 0 1 1.5 1.5V18H19M9 18h6");
}

.nc0vl2seq {
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM7 3.5h10v3H7Zm5 3v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

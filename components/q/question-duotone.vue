<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0q4x4bbw"/><path class="tjvuacchn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:question-duotone" /></template>
<style>
.n0q4x4bbw {
  stroke-linejoin: miter;
  d: path("M8 9C8 6.7909 9.7909 5 12 5C14.2091 5 16 6.7909 16 9C16 10.6148 15.029 12.0712 13.5385 12.6923C12.6068 13.0805 12 13.9907 12 15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tjvuacchn {
  fill: currentColor;
  d: path("M13 19C13 19.5523 12.5523 20 12 20C11.4477 20 11 19.5523 11 19C11 18.4477 11.4477 18 12 18C12.5523 18 13 18.4477 13 19Z");
  stroke: none;
}

</style>

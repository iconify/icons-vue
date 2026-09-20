<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t01ameb9s"/><path class="wa1c01bfg"/><path class="zgtvbjo0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:volcano-peak-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t01ameb9s {
  fill: currentColor;
  d: path("m4 20 7 -7h3l7 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wa1c01bfg {
  d: path("m4 20 7 -7h3l7 7Z");
}

.zgtvbjo0h {
  d: path("m9 10 3 -3 3 3");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="amc56wyii"/><path class="t4jf2kbbc"/><path class="db30e8q5x"/><path class="d_4x3homz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:travel-sim-duotone-regular" /></template>
<style>
.amc56wyii {
  fill: currentColor;
  d: path("M6 3h10l3 3v15H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d_4x3homz {
  d: path("M9 10h7v7H9Z");
}

.db30e8q5x {
  d: path("M6 3h10l3 3v15H6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t4jf2kbbc {
  fill: currentColor;
  d: path("M9 10h7v7H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

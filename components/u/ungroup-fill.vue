<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lz2vtpetf"/><path clip-rule="evenodd" class="y2h4di6wf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ungroup-fill" /></template>
<style>
.lz2vtpetf {
  d: path("M8 12H5C3.8954 12 3 12.8954 3 14V19C3 20.1046 3.8954 21 5 21H10C11.1046 21 12 20.1046 12 19V16M8 3V5M3 8H5M16 19V21M19 16H21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y2h4di6wf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 2L19 2C20.6569 2 22 3.3431 22 5L22 10C22 11.6569 20.6569 13 19 13L14 13C12.3431 13 11 11.6569 11 10L11 5C11 3.3431 12.3431 2 14 2Z");
  stroke: none;
}

</style>

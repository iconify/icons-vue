<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zgn95dw-s"/><path class="qabp2ib4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:refrigerator-mini" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qabp2ib4x {
  fill: currentColor;
  d: path("M7 6C7 6.5523 6.5523 7 6 7C5.4477 7 5 6.5523 5 6C5 5.4477 5.4477 5 6 5C6.5523 5 7 5.4477 7 6Z");
  stroke: none;
}

.zgn95dw-s {
  d: path("M5 20L4 20C2.8954 20 2 19.1046 2 18L2 4C2 2.8954 2.8954 2 4 2L20 2C21.1046 2 22 2.8954 22 4L22 18C22 19.1046 21.1046 20 20 20L5 20ZM2 10L22 10M5 20L5 22M19 20L19 22M6 20L6 18C6 16.8954 6.8954 16 8 16M10 20L10 18C10 16.8954 9.1046 16 8 16M8 16L8 14M14 20L14 18C14 16.8954 14.8954 16 16 16M18 20L18 18C18 16.8954 17.1046 16 16 16M16 16L16 14");
}

</style>

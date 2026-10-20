<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="f30cotb8m"/><path class="jeua-kmfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vector-square-fill" /></template>
<style>
.f30cotb8m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 2L6 2C7.1046 2 8 2.8954 8 4L8 6C8 7.1046 7.1046 8 6 8L4 8C2.8954 8 2 7.1046 2 6L2 4C2 2.8954 2.8954 2 4 2ZM18 2L20 2C21.1046 2 22 2.8954 22 4L22 6C22 7.1046 21.1046 8 20 8L18 8C16.8954 8 16 7.1046 16 6L16 4C16 2.8954 16.8954 2 18 2ZM4 16L6 16C7.1046 16 8 16.8954 8 18L8 20C8 21.1046 7.1046 22 6 22L4 22C2.8954 22 2 21.1046 2 20L2 18C2 16.8954 2.8954 16 4 16ZM18 16L20 16C21.1046 16 22 16.8954 22 18L22 20C22 21.1046 21.1046 22 20 22L18 22C16.8954 22 16 21.1046 16 20L16 18C16 16.8954 16.8954 16 18 16Z");
  stroke: none;
}

.jeua-kmfe {
  d: path("M7 5L17 5M7 19L17 19M5 7L5 17M19 7L19 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

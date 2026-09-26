<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hf5oswbse"/><path class="cqf64201r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tube-two-tone" /></template>
<style>
.cqf64201r {
  d: path("M10 2L14 2C14.5523 2 15 2.4477 15 3L15 19C15 20.6569 13.6569 22 12 22C10.3431 22 9 20.6569 9 19L9 3C9 2.4477 9.4477 2 10 2ZM8 2L16 2M9 14L15 14");
}

.hf5oswbse {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 1L14 1C15.1046 1 16 1.8954 16 3L16 19C16 21.2091 14.2091 23 12 23C9.7909 23 8 21.2091 8 19L8 3C8 1.8954 8.8954 1 10 1Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

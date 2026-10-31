<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="em83ztn-p"/><path class="aq552ibfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:microwave-fill" /></template>
<style>
.aq552ibfv {
  d: path("M6 19L6 21M18 19L18 21");
}

.em83ztn-p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2L19 2C21.2092 2 23 3.7908 23 6L23 16C23 18.2092 21.2092 20 19 20L5 20C2.7908 20 1 18.2092 1 16L1 6C1 3.7908 2.7908 2 5 2ZM8 6C6.3431 6 5 7.3431 5 9L5 13C5 14.6569 6.3431 16 8 16L12 16C13.6569 16 15 14.6569 15 13L15 9C15 7.3431 13.6569 6 12 6L8 6ZM19 9C19 8.4477 18.5523 8 18 8C17.4477 8 17 8.4477 17 9C17 9.5523 17.4477 10 18 10C18.5523 10 19 9.5523 19 9ZM19 13C19 12.4477 18.5523 12 18 12C17.4477 12 17 12.4477 17 13C17 13.5523 17.4477 14 18 14C18.5523 14 19 13.5523 19 13Z");
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

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ihgbwbbyj"/><path class="fnbgpcbhf"/><path class="sb40gqbga"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:staircase-duotone-regular" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.fnbgpcbhf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ihgbwbbyj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21v-4h5v-4h5V9h5V5h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sb40gqbga {
  d: path("M3 21v-4h5v-4h5V9h5V5h3");
}

</style>

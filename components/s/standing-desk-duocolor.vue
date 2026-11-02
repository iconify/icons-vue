<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w1oesmbrj"/><path class="j1pn58dah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:standing-desk-duocolor" /></template>
<style>
.j1pn58dah {
  d: path("M3 20v-2a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v2M11 6a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2Zm5 6v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w1oesmbrj {
  stroke-opacity: 0.4;
  d: path("m3 6l2-2l2 2m-4 4l2 2l2-2");
}

</style>

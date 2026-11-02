<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ro03-qbff"/><path class="damovmc1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-outgoing-duocolor-round" /></template>
<style>
.damovmc1h {
  d: path("M3 5a2 2 0 0 1 2-2h1c1.691 0 3.275 1.188 4 3c.693 1.733.693 3.307 0 4a2.12 2.12 0 0 0 0 3l2 2a2.12 2.12 0 0 0 3 0c.64-.64 1.72-1 3-1h1c1.105 0 2 1.79 2 4v1a2 2 0 0 1-2 2C10.163 21 3 13.837 3 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ro03-qbff {
  stroke-opacity: 0.4;
  d: path("M17 3h4v4m0-4l-6 6");
}

</style>

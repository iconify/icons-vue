<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="quhf9pj8o"/><path class="vp-ly0bxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shovel-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.quhf9pj8o {
  stroke-opacity: 0.4;
  d: path("m11 13l6-6m-2-2l4 4");
}

.vp-ly0bxv {
  d: path("m11 13l2 2a1.414 1.414 0 0 1 0 2c-.64.64-1.36 1-2 1H9a3 3 0 0 1-3-3v-2c0-.64.36-1.36 1-2a1.414 1.414 0 0 1 2 0z");
}

</style>

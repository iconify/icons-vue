<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eiuvhjh8d"/><path class="p-7n8tmgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-close-duocolor" /></template>
<style>
.eiuvhjh8d {
  stroke-opacity: 0.4;
  d: path("m15 9l6 6m0-6l-6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-7n8tmgz {
  d: path("M11 6v12c0 .738-.631 1.369-1 1l-2-2c-.64-.64-1.36-1-2-1H5a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2h1c.64 0 1.36-.36 2-1l2-2c.369-.369 1 .262 1 1");
}

</style>

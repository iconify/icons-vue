<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b3o8aj64t"/><path class="s-207ebhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:upload-duocolor" /></template>
<style>
.b3o8aj64t {
  stroke-opacity: 0.4;
  d: path("M4 16v2a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s-207ebhv {
  d: path("m16 8l-4-4l-4 4m4-4v12");
}

</style>

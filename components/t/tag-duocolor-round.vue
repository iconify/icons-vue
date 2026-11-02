<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a-7__ob0f"/><path class="a9m3p5bvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-duocolor-round" /></template>
<style>
.a-7__ob0f {
  stroke-opacity: 0.4;
  d: path("M8 9a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.a9m3p5bvt {
  d: path("M8 4h2c1.28 0 2.36.36 3 1l4 4a4.243 4.243 0 0 1 0 6l-2 2a4.243 4.243 0 0 1-6 0l-4-4c-.64-.64-1-1.72-1-3V8a4 4 0 0 1 4-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eozf1-bjg"/><path class="fj7td4mmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-upload-duocolor" /></template>
<style>
.eozf1-bjg {
  stroke-opacity: 0.4;
  d: path("m15 14l-3-3l-3 3m3-3v6");
}

.fj7td4mmx {
  d: path("M5 6c.613-1.226 1.387-2 2-2h10c.613 0 1.387.774 2 2l1 2v10a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V8zM4 8h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

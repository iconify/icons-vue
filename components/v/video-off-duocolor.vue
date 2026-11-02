<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p52u7fomt"/><path class="osw0so33h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-off-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.osw0so33h {
  d: path("M15 16a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2m6 0h2a2 2 0 0 1 2 2v2m0 0l4-2c.919-.46 2 .081 2 1v6c0 .284.17-.194 0 0");
}

.p52u7fomt {
  stroke-opacity: 0.4;
  d: path("m2 3l19 19");
}

</style>

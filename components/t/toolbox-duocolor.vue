<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fgrie8yre"/><path class="hkdwk9r2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toolbox-duocolor" /></template>
<style>
.fgrie8yre {
  stroke-opacity: 0.4;
  d: path("M9 8V5a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3");
}

.hkdwk9r2u {
  d: path("M3 10a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm0 4h18M8 12v4m8-4v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

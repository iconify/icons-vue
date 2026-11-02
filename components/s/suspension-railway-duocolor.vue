<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ahy_qimtf"/><path class="papzy6blx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:suspension-railway-duocolor" /></template>
<style>
.ahy_qimtf {
  stroke-opacity: 0.4;
  d: path("M3 4h18M7 4v5m8-5v5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.papzy6blx {
  d: path("M12 20H5a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2h12l4 4v5a2 2 0 0 1-2 2zm-9-4h18M11 9v7");
}

</style>

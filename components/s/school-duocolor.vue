<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ltbozbc2i"/><path class="gs_pes75a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:school-duocolor" /></template>
<style>
.gs_pes75a {
  d: path("m4 7l8-4l8 4M6 6v5l-3 2v6a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-6l-3-2V6");
}

.ltbozbc2i {
  stroke-opacity: 0.4;
  d: path("M10 10a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 11v-3a2 2 0 1 1 4 0v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

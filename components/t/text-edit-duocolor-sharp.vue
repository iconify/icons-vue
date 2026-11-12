<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fm21oiyer"/><path class="pycm0tbsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-edit-duocolor-sharp" /></template>
<style>
.fm21oiyer {
  stroke-opacity: 0.4;
  d: path("m3 21l3-3l3 3m4 0h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pycm0tbsr {
  d: path("M9 15v-3l9-9l3 3l-9 9zm6-9l3 3");
}

</style>

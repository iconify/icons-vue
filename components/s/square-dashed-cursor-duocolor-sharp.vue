<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jpt160bdm"/><path class="m16i06_lb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-cursor-duocolor-sharp" /></template>
<style>
.jpt160bdm {
  stroke-opacity: 0.4;
  d: path("m9 9l12 4l-4 1l3 3l-3 3l-3-3l-1 4z");
}

.m16i06_lb {
  d: path("M3 6V3h3m12 0h3v3M6 21H3v-3m7-15h4M3 14v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

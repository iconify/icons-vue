<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kodnftbvm"/><path class="ucl0xbbjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top-open-dashed" /></template>
<style>
.kodnftbvm {
  d: path("M3 9V6C3 4.34315 4.34315 3 6 3H18C19.6569 3 21 4.34315 21 6V9H3ZM3 18C3 19.6569 4.34315 21 6 21M18 21C19.6569 21 21 19.6569 21 18M3 13V14M21 13V14M10.5 21H13.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ucl0xbbjf {
  d: path("M9 13L12 16L15 13");
}

</style>

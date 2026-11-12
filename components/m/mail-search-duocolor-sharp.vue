<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z6y07wbqv"/><path class="gug78lu7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-duocolor-sharp" /></template>
<style>
.gug78lu7c {
  d: path("M21 14v5H3V5h7M3 5l6 6h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z6y07wbqv {
  stroke-opacity: 0.4;
  d: path("M14 4a2.828 2.828 0 1 1 4 4a2.828 2.828 0 0 1-4-4m4 4l3 3");
}

</style>

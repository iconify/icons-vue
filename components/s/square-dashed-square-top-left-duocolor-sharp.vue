<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jru4xkb0p"/><path class="ifns3qbmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-left-duocolor-sharp" /></template>
<style>
.ifns3qbmc {
  d: path("M18 3h3v3m0 12v3h-3M6 21H3v-3m18-8v4m-7 7h-4");
}

.jru4xkb0p {
  stroke-opacity: 0.4;
  d: path("M3 3h11v11H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

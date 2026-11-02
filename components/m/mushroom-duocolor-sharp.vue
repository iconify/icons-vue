<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hiyfnwbgc"/><path class="w-mn8bmrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mushroom-duocolor-sharp" /></template>
<style>
.hiyfnwbgc {
  stroke-opacity: 0.4;
  d: path("M10 11v8a2 2 0 1 0 4 0v-8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w-mn8bmrv {
  d: path("M4 11a8 8 0 1 1 16 0Z");
}

</style>

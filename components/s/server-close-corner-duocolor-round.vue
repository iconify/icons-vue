<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l9ycfeb_j"/><path class="z7y7a6b7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-close-corner-duocolor-round" /></template>
<style>
.l9ycfeb_j {
  stroke-opacity: 0.4;
  d: path("m14 14l6 6m0-6l-6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z7y7a6b7p {
  d: path("M3 7a3 3 0 0 1 3-3h12a3 3 0 0 1 0 6H6a3 3 0 0 1-3-3m0 7h6m0 6H6a3 3 0 0 1-3-3v-3m4-7h.01M7 17h.01");
}

</style>

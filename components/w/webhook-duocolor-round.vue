<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jzu91sbxz"/><path class="zw1gf9qvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:webhook-duocolor-round" /></template>
<style>
.jzu91sbxz {
  stroke-opacity: 0.4;
  d: path("M16 7a4 4 0 1 0-8 0v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zw1gf9qvq {
  d: path("M4 17a4 4 0 1 0 8 0h4m0 4a4 4 0 1 0 0-8a4 4 0 0 1-4-4V7");
}

</style>

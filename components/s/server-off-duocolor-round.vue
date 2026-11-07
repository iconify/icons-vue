<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e72o9db0j"/><path class="lbjmgof1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-duocolor-round" /></template>
<style>
.e72o9db0j {
  stroke-opacity: 0.4;
  d: path("M7 17h.01M2 2l20 20");
}

.lbjmgof1c {
  d: path("M10 10H6a3 3 0 0 1-1.562-5.562M10 4h8a3 3 0 0 1 0 6h-2m3.562 9.562c-.455.278-.99.438-1.562.438H6a3 3 0 0 1 0-6h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

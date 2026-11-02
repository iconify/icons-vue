<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wo7q3jbvq"/><path class="wpkh1qb7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sim-card-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wo7q3jbvq {
  stroke-opacity: 0.4;
  d: path("M9 10a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1Zm0 3h6");
}

.wpkh1qb7b {
  d: path("M5 12V5a2 2 0 0 1 2-2h7c.64 0 1.36.36 2 1l2 2c.64.64 1 1.36 1 2v11a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2z");
}

</style>

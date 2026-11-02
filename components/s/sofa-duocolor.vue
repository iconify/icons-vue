<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kh84thbny"/><path class="bz1wzorsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sofa-duocolor" /></template>
<style>
.bz1wzorsr {
  d: path("M3 11v4a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-4a2 2 0 1 0-4 0a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2a2 2 0 1 0-4 0m2 6v2m14-2v2M12 5v8");
}

.kh84thbny {
  stroke-opacity: 0.4;
  d: path("M5 9V7a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

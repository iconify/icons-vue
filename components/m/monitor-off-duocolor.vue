<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q76_okbsb"/><path class="x9cisqbvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-off-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q76_okbsb {
  stroke-opacity: 0.4;
  d: path("M9 20h6M3 2l19 19");
}

.x9cisqbvp {
  d: path("M18 17H6a2 2 0 0 1-2-2V6a2 2 0 0 1 1.177-1.823M11 4h7a2 2 0 0 1 2 2v7");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eba0prbjj"/><path class="ktqe5bcpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ruler-duocolor" /></template>
<style>
.eba0prbjj {
  stroke-opacity: 0.4;
  d: path("m5 13l2 2m2-6l2 2m2-6l2 2");
}

.ktqe5bcpf {
  d: path("m9 9l5-5a1.414 1.414 0 0 1 2 0l4 4a1.414 1.414 0 0 1 0 2L10 20a1.414 1.414 0 0 1-2 0l-4-4a1.414 1.414 0 0 1 0-2z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

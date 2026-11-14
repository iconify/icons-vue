<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ggbcuxbun"/><path class="oele413pe"/><path class="nckme7bam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:prompt-copy" /></template>
<style>
.ggbcuxbun {
  d: path("M4.5 17.5V5A2.5 2.5 0 0 1 7 2.5h8.5");
}

.nckme7bam {
  d: path("M11.5 10.5h5a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H13l-2 2v-2a1 1 0 0 1-.5-1v-3a1 1 0 0 1 1-1Z");
}

.oele413pe {
  d: path("M8 7h12v14.5H8Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

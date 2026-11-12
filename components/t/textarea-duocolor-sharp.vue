<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vgl54wu5w"/><path class="cbbods3vk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:textarea-duocolor-sharp" /></template>
<style>
.cbbods3vk {
  d: path("M3 3h18v18H3Zm4 4h10M7 11h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vgl54wu5w {
  stroke-opacity: 0.4;
  d: path("m12 18l6-6m-1 6l1-1");
}

</style>

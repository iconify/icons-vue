<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x3jwz5nip"/><path class="uquxg97-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rainbow-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uquxg97-c {
  d: path("M3 18v-3a9 9 0 0 1 18 0v3M9 18v-3a3 3 0 0 1 6 0v3");
}

.x3jwz5nip {
  stroke-opacity: 0.4;
  d: path("M6 18v-3a6 6 0 1 1 12 0v3");
}

</style>

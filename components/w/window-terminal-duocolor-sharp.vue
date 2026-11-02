<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wm4aheb3h"/><path class="vrlw9abfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-terminal-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vrlw9abfp {
  d: path("M3 8V4h18v16H3zm0 0h18");
}

.wm4aheb3h {
  stroke-opacity: 0.4;
  d: path("m7 12l2 2l-2 2m6 0h4");
}

</style>

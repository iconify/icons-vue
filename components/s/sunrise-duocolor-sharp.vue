<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wv693ghkj"/><path class="j-wxgjbtz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sunrise-duocolor-sharp" /></template>
<style>
.j-wxgjbtz {
  d: path("M9 17a3 3 0 0 1 6 0M3 17h2m14 0h2M3 21h18M5 10l2 2m12-2l-2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wv693ghkj {
  stroke-opacity: 0.4;
  d: path("m15 6l-3-3l-3 3m3-3v7");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p-gptrbun"/><path class="x2k-zab0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-off-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-gptrbun {
  stroke-opacity: 0.4;
  d: path("M12 18v3M5 10v1a7 7 0 0 0 11.95 4.95M3 2l19 19");
}

.x2k-zab0o {
  d: path("M9 8v3a3 3 0 0 0 5.121 2.121M15 8V6a3 3 0 0 0-4.562-2.562");
}

</style>

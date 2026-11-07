<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xznqv2b9z"/><path class="bfdqbsi5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-off-duotone-round" /></template>
<style>
.bfdqbsi5k {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 8v3a3 3 0 0 0 5.121 2.121M15 8V6a3 3 0 0 0-4.562-2.562M12 18v3M5 10v1a7 7 0 0 0 11.95 4.95M3 2l19 19");
}

.ft5dv1b6b {
  fill: none;
}

.xznqv2b9z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10.438 3.438A3 3 0 0 1 15 6v2Zm3.683 9.683A3 3 0 0 1 9 11V8Z");
}

</style>

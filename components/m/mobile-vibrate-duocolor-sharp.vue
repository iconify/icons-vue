<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cbt8ot9gw"/><path class="ctvcln5hp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-vibrate-duocolor-sharp" /></template>
<style>
.cbt8ot9gw {
  stroke-opacity: 0.4;
  d: path("m3 6l1 3l-1 3l1 3l-1 3M21 6l-1 3l1 3l-1 3l1 3");
}

.ctvcln5hp {
  d: path("M7 3h10v18H7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

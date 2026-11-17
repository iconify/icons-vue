<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qgo3vobus"/><path class="r1etxz8pb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-check-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qgo3vobus {
  stroke-opacity: 0.4;
  d: path("m9 9l2 2l4-4");
}

.r1etxz8pb {
  d: path("M12 21H7a4 4 0 0 1-4-4V7a4 4 0 0 1 4-4h8c1.28 0 2.36.36 3 1l2 2c.64.64 1 1.72 1 3v8a4 4 0 0 1-4 4zm-5 0v-3a4 4 0 0 1 4-4h2a4 4 0 0 1 4 4v3");
}

</style>

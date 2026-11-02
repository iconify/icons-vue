<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n-31ttcxg"/><path class="rxkg3ygff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-duocolor-round" /></template>
<style>
.n-31ttcxg {
  stroke-opacity: 0.4;
  d: path("m11 13l3-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rxkg3ygff {
  d: path("M12 6L6 8c-1.107.369-.476 2.262 1 3l2 1a6.7 6.7 0 0 1 3 3l1 2c.738 1.476 2.631 2.107 3 1l4-12c.412-1.236-.764-2.412-2-2z");
}

</style>

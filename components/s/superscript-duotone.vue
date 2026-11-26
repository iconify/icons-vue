<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r7pdf_baq"/><path class="qcfo2qbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:superscript-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qcfo2qbfo {
  d: path("M16.75 6.1L19 4V11M16 11H22");
}

.r7pdf_baq {
  stroke-opacity: 0.4;
  d: path("M2 8L12 20M12 8L2 20");
}

</style>

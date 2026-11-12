<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hozb15e2k"/><path class="hsrklbr3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-split-duocolor-round" /></template>
<style>
.hozb15e2k {
  stroke-opacity: 0.4;
  d: path("M12 7v5m-6 8v-4a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v4M3 17l3 3l3-3m6 0l3 3l3-3");
}

.hsrklbr3a {
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

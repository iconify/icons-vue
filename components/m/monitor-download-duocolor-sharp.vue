<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l2mfjsrty"/><path class="poo2p_bsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-download-duocolor-sharp" /></template>
<style>
.l2mfjsrty {
  stroke-opacity: 0.4;
  d: path("m9 11l3 3l3-3m-3 3V7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.poo2p_bsk {
  d: path("M4 4h16v13H4Zm5 16h6");
}

</style>

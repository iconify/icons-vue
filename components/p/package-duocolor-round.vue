<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wo998-bfj"/><path class="jcpaywizy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-duocolor-round" /></template>
<style>
.jcpaywizy {
  d: path("M4 8v8a4 4 0 0 0 4 4h8a4 4 0 0 0 4-4V8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wo998-bfj {
  stroke-opacity: 0.4;
  d: path("m4 8l1-2c.613-1.226 1.774-2 3-2h8c1.226 0 2.387.774 3 2l1 2M4 8h16");
}

</style>

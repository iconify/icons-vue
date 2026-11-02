<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jcvgmbc_x"/><path class="yzbanlotk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:qr-code-duocolor-sharp" /></template>
<style>
.jcvgmbc_x {
  stroke-opacity: 0.4;
  d: path("M14 14h3m3 0h.01M14 18v2m4-2h2v2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yzbanlotk {
  d: path("M4 4h6v6H4Zm10 0h6v6h-6ZM4 14h6v6H4Z");
}

</style>

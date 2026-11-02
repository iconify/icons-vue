<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vc_s7sh1o"/><path class="eyyyeghth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tablet-button-duocolor-sharp" /></template>
<style>
.eyyyeghth {
  d: path("M4 3h16v18H4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vc_s7sh1o {
  stroke-opacity: 0.4;
  d: path("M12 18h.01");
}

</style>

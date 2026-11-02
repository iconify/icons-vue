<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wbmm5u2vb"/><path class="trd767bez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:synagogue-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.trd767bez {
  d: path("M12 21H6a2 2 0 0 1-2-2V9c0-.613.774-1.387 2-2l6-3l6 3c1.226.613 2 1.387 2 2v10a2 2 0 0 1-2 2z");
}

.wbmm5u2vb {
  stroke-opacity: 0.4;
  d: path("m12 9l3.464 6H8.536Zm0 8l3.464-6H8.536Z");
}

</style>

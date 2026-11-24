<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d_vdeimer"/><path class="c525hvboc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:receipt-plus-duocolor-round" /></template>
<style>
.c525hvboc {
  d: path("M12 3h4a4 4 0 0 1 4 4v14l-4-2l-4 2l-4-2l-4 2V7a4 4 0 0 1 4-4z");
}

.d_vdeimer {
  stroke-opacity: 0.4;
  d: path("M9 11h6m-3-3v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

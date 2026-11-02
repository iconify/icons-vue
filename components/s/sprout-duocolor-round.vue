<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l_vhlnb1v"/><path class="lq2p-57iz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sprout-duocolor-round" /></template>
<style>
.l_vhlnb1v {
  stroke-opacity: 0.4;
  d: path("M12 20V10");
}

.lq2p-57iz {
  d: path("M12 10a6 6 0 0 0-6-6H3v2a6 6 0 0 0 6 6h3Zm0 4a6 6 0 0 1 6-6h3v1a6 6 0 0 1-6 6h-3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>

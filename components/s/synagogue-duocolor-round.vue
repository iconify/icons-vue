<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wbmm5u2vb"/><path class="aob6o6blk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:synagogue-duocolor-round" /></template>
<style>
.aob6o6blk {
  d: path("M12 21H8a4 4 0 0 1-4-4v-7c0-1.226.774-2.387 2-3l4-2a4.47 4.47 0 0 1 4 0l4 2c1.226.613 2 1.774 2 3v7a4 4 0 0 1-4 4z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wbmm5u2vb {
  stroke-opacity: 0.4;
  d: path("m12 9l3.464 6H8.536Zm0 8l3.464-6H8.536Z");
}

</style>

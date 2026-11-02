<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oe7_vcbri"/><path class="i4ft-wb3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-pine-duocolor-round" /></template>
<style>
.i4ft-wb3e {
  d: path("m14 7l4 4c.369.369-.262 1-1 1h-2l5 5c.369.369-.262 1-1 1H5c-.738 0-1.369-.631-1-1l5-5H7c-.738 0-1.369-.631-1-1l4-4H7l5-4l5 4z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oe7_vcbri {
  stroke-opacity: 0.4;
  d: path("M12 18v3");
}

</style>

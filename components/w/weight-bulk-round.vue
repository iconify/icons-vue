<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d6qr-0brt"/><path class="algumwb1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:weight-bulk-round" /></template>
<style>
.algumwb1d {
  d: path("M9 6.019V6a3.004 3.004 0 0 1 3-3h.001c1.657.001 3 1.343 2.999 3v.001A3 3 0 0 1 12 9h-.001A3 3 0 0 1 9 6.019M11.999 5a1 1 0 0 0-.711.297a.96.96 0 0 0-.288.697v.011A1 1 0 1 0 12 5Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.d6qr-0brt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 7h5c1.73 0 3.388 1.003 3.949 2.684l2 6c.635 1.906-.259 3.95-2.033 4.858A4.16 4.16 0 0 1 16 21H8a4.16 4.16 0 0 1-1.916-.458c-1.774-.908-2.668-2.952-2.033-4.858l2-6c.228-.683.581-1.327 1.093-1.839C7.637 7.352 8.29 7 9 7");
}

</style>

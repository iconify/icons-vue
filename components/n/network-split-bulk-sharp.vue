<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j6-cpacfl"/><path class="mxr85zdjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-split-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j6-cpacfl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 5a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

.mxr85zdjr {
  d: path("M5 12a1 1 0 0 1 1-1h5V7a1 1 0 0 1 2 0v4h5a1 1 0 0 1 1 1v5.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L17 17.586V13H7v4.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.413.001h-.001l-3-3.001a.999.999 0 1 1 1.414-1.414L5 17.586Z");
}

</style>

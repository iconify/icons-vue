<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bs7fszbpp"/><path class="hf_3n7brb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:replace-bulk-round" /></template>
<style>
.bs7fszbpp {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 17a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.hf_3n7brb {
  d: path("M7 7v.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0l-3-3a.999.999 0 1 1 1.414-1.414L5 7.586V7a5 5 0 0 1 5-5h1a1 1 0 0 1 0 2h-1a3 3 0 0 0-3 3m7 0V4.999A3 3 0 0 1 17 2h2a3.004 3.004 0 0 1 3 3v2a3.004 3.004 0 0 1-3 3h-2a3 3 0 0 1-3-3m3 1h2a1 1 0 0 0 1-1V4.999A1 1 0 0 0 19 4h-2.001A1 1 0 0 0 16 5v2a.997.997 0 0 0 1 1");
}

</style>

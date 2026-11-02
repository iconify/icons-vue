<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rms4wkbjj"/><path class="i5s2ezmxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wallbox-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i5s2ezmxp {
  d: path("M9.707 6.707L8.414 8H10a1.002 1.002 0 0 1 .707 1.707l-3 3a.999.999 0 1 1-1.414-1.414L7.586 10H6a1.002 1.002 0 0 1-.707-1.707l3-3a.999.999 0 1 1 1.414 1.414M9 15v3h9v-5a1 1 0 0 1 2 0v6a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0");
}

.rms4wkbjj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h10a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1m14 4h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1");
}

</style>

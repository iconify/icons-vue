<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qr_62qvog"/><path class="i11ylvpcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:presentation-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i11ylvpcu {
  d: path("M21 2a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm-3.293 18.293a.999.999 0 1 1-1.414 1.414L12 17.414l-4.293 4.293a.999.999 0 1 1-1.414-1.414l5-5a1 1 0 0 1 1.414 0Z");
}

.qr_62qvog {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2h14a1 1 0 0 1 1 1v9a5 5 0 0 1-5 5H9a5 5 0 0 1-5-5V3a1 1 0 0 1 1-1");
}

</style>

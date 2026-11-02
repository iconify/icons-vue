<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bpzb5ebjn"/><path class="ctynhw5wp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-download-corner-bulk-round" /></template>
<style>
.bpzb5ebjn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 13v8a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v3a1 1 0 0 1-1 1a2 2 0 0 0-2 2");
}

.ctynhw5wp {
  d: path("m16.293 21.707l-3-3a1 1 0 0 1 1.414-1.414L16 18.586V13a1 1 0 0 1 2 0v5.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>

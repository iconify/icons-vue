<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vwfa76uss"/><path class="jf11dvboh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sunrise-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jf11dvboh {
  d: path("m5.707 9.293l2 2a.999.999 0 1 1-1.414 1.414l-2-2a.999.999 0 1 1 1.414-1.414m14 1.414l-2 2a.999.999 0 1 1-1.414-1.414l2-2a.999.999 0 1 1 1.414 1.414M8 17a4 4 0 0 1 8 0a1 1 0 0 1-2 0a2 2 0 1 0-4 0a1 1 0 0 1-2 0m-5-1h2a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m18 0a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2ZM3 20h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

.vwfa76uss {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 5.414V10a1 1 0 0 1-2 0V5.414L9.707 6.707a.999.999 0 1 1-1.414-1.414l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414Z");
}

</style>

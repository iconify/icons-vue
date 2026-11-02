<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lsxhw2bwk"/><path class="gzq1g682w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-minus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gzq1g682w {
  d: path("M10 13h4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2");
}

.lsxhw2bwk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m15.84 5.153l5.5 9A4.5 4.5 0 0 1 17.5 21h-11a4.5 4.5 0 0 1-3.84-6.847l5.5-9a4.502 4.502 0 0 1 7.68 0");
}

</style>

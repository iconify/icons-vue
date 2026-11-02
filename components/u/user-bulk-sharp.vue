<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r_885cq1y"/><path class="ildyyli-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ildyyli-y {
  d: path("M5 21a7 7 0 1 1 14 0a1 1 0 0 1-2 0a5.001 5.001 0 0 0-10 0a1 1 0 0 1-2 0");
}

.r_885cq1y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 7a5 5 0 1 1 10.001.001A5 5 0 0 1 7 7m11 15H6a1 1 0 0 1-1-1a6.9 6.9 0 0 1 .551-2.725A6.9 6.9 0 0 1 7.05 16.05A6.97 6.97 0 0 1 12 14c1.862 0 3.636.731 4.95 2.05a6.9 6.9 0 0 1 1.499 2.225c.366.862.554 1.789.551 2.725a1 1 0 0 1-1 1");
}

</style>

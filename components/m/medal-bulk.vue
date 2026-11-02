<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xuaf02sie"/><path class="uqainnuqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:medal-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uqainnuqy {
  d: path("M5.051 3.316A1.002 1.002 0 0 1 6 2h4c.379 0 .725.214.894.553L12 4.764l1.106-2.211A1 1 0 0 1 14 2h4a1.002 1.002 0 0 1 .949 1.316l-3 9a1.001 1.001 0 0 1-1.898-.632L16.613 4h-1.995l-1.724 3.447a.998.998 0 0 1-1.788 0L9.382 4H7.387l2.562 7.684a1.001 1.001 0 0 1-1.898.632Z");
}

.xuaf02sie {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.162 11.678a6 6 0 1 1-8.324 0L5.051 3.316A1.002 1.002 0 0 1 6 2h4c.379 0 .725.214.894.553L12 4.764l1.106-2.211A1 1 0 0 1 14 2h4a1.002 1.002 0 0 1 .949 1.316Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u43dghy1a"/><path class="r6c1f9bot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r6c1f9bot {
  d: path("m5.707 1.293l17 17a.999.999 0 1 1-1.414 1.414L14.586 13H8a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0v-2a3 3 0 0 1 3-3h4.586L4.293 2.707a.999.999 0 1 1 1.414-1.414");
}

.u43dghy1a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.351 2.108A2 2 0 0 1 10 2h4a2 2 0 0 1 2 2v3c0 .472-.166.927-.47 1.288ZM4 15h4a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2m14 0l4 4v1a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2Z");
}

</style>

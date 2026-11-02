<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ikb8-47xq"/><path class="yatj0teve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:redo-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ikb8-47xq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.384 12a7.617 7.617 0 1 1 15.233 0a7.617 7.617 0 1 1-15.233 0");
}

.yatj0teve {
  d: path("M17.271 8a6.617 6.617 0 0 0-11.352 6.606a6.62 6.62 0 0 0 4.833 3.889a6.606 6.606 0 0 0 7.329-3.889a.999.999 0 1 1 1.838.788a8.613 8.613 0 0 1-14.011 2.698A8.615 8.615 0 0 1 18 5.817V3a1 1 0 0 1 2 0v6a.997.997 0 0 1-1 1h-6a1 1 0 0 1 0-2Z");
}

</style>

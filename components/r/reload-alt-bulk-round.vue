<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ikb8-47xq"/><path class="frstq-lyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:reload-alt-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.frstq-lyp {
  d: path("M17.271 8a6.62 6.62 0 0 0-4.823-2.599a6.6 6.6 0 0 0-6.529 3.993a1 1 0 0 1-.548.534a.999.999 0 0 1-1.29-1.322A8.615 8.615 0 0 1 18 5.817V3a1 1 0 0 1 2 0v6a.997.997 0 0 1-1 1h-6a1 1 0 0 1 0-2ZM6 18.183V21a1 1 0 0 1-2 0v-6a1 1 0 0 1 .988-1H11a1 1 0 0 1 0 2H6.729a6.62 6.62 0 0 0 6.076 2.568a6.62 6.62 0 0 0 5.276-3.962a.999.999 0 1 1 1.838.788A8.615 8.615 0 0 1 6 18.183");
}

.ikb8-47xq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.384 12a7.617 7.617 0 1 1 15.233 0a7.617 7.617 0 1 1-15.233 0");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ajvp0bcfw"/><path class="rwm2e67op"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:save-check-bulk-sharp" /></template>
<style>
.ajvp0bcfw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m17.707 2.293l4 4A1 1 0 0 1 22 7v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h14c.265 0 .52.105.707.293");
}

.cuyn6tgcc {
  fill: currentColor;
}

.rwm2e67op {
  d: path("M9.707 8.293L11 9.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414M6 21v-7a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v7a1 1 0 0 1-2 0v-6H8v6a1 1 0 0 1-2 0");
}

</style>

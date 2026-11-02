<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aphsmmbcu"/><path class="xxu-ldbnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:satellite-dish-bulk-round" /></template>
<style>
.aphsmmbcu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m5.707 10.293l8 8a1 1 0 0 1 0 1.414a6.6 6.6 0 0 1-2.203 1.462A6.6 6.6 0 0 1 9 21.657a6.64 6.64 0 0 1-4.707-1.95A6.64 6.64 0 0 1 2.343 15a6.6 6.6 0 0 1 .488-2.504a6.6 6.6 0 0 1 1.462-2.203a.997.997 0 0 1 1.414 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.xxu-ldbnm {
  d: path("M12 3a1 1 0 0 1 1-1a9 9 0 0 1 9 9a1 1 0 0 1-2 0a6.97 6.97 0 0 0-2.05-4.95a6.9 6.9 0 0 0-2.226-1.5A6.95 6.95 0 0 0 13 4a1 1 0 0 1-1-1m0 4a1 1 0 0 1 1-1a5 5 0 0 1 3.536 1.464A4.97 4.97 0 0 1 18 11a1 1 0 0 1-2 0c0-.801-.31-1.558-.879-2.121A2.96 2.96 0 0 0 13 8a1 1 0 0 1-1-1m-3.707 7.293l4-4a.999.999 0 1 1 1.414 1.414l-4 4a.999.999 0 1 1-1.414-1.414");
}

</style>

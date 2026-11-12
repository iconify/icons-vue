<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ceffiumzh"/><path class="g95sh6jyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:websocket-bulk-round" /></template>
<style>
.ceffiumzh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.707 7.293a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L14.586 9H7a1 1 0 0 1 0-2h7.586l-1.293-1.293a.999.999 0 1 1 1.414-1.414ZM9.414 15H17a1 1 0 0 1 0 2H9.414l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.g95sh6jyd {
  d: path("M4 21a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm18 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Z");
}

</style>

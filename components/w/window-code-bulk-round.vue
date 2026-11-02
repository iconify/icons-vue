<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l3h0twbhh"/><path class="y3w3esb2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-code-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l3h0twbhh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5Z");
}

.y3w3esb2q {
  d: path("M3 7h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m7.707 6.707L9.414 15l1.293 1.293a.999.999 0 1 1-1.414 1.414l-2-2a.997.997 0 0 1 0-1.414l2-2a.999.999 0 1 1 1.414 1.414m4-1.414l2 2a1 1 0 0 1 0 1.414l-2 2a.999.999 0 1 1-1.414-1.414L14.586 15l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zjfit0btt"/><path class="hlju7j68b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:route-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hlju7j68b {
  d: path("M7 7v4h11a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H8a1 1 0 0 1 0-2h9v-4H6a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h9.171a3 3 0 1 1 0 2Zm10-1a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.zjfit0btt {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>

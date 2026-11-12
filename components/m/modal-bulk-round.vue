<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l3h0twbhh"/><path class="pd1_pvszv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:modal-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l3h0twbhh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5Z");
}

.pd1_pvszv {
  d: path("M6 10a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3Z");
}

</style>

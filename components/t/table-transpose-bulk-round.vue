<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f5yykimei"/><path class="noe1vbbmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-transpose-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f5yykimei {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 2h6a3 3 0 1 1 0 6h-6a3 3 0 1 1 0-6M2 13a3 3 0 1 1 6 0v6a3 3 0 1 1-6 0Z");
}

.noe1vbbmn {
  d: path("M13 19v-4a1 1 0 0 1 2 0v1.586l4.293-4.293a.999.999 0 1 1 1.414 1.414L16.414 18H18a1 1 0 0 1 0 2h-4a1 1 0 0 1-1-1");
}

</style>

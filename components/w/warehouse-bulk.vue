<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d6_p683ee"/><path class="lfxipybne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.d6_p683ee {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 21V11c.001-1.348 1.478-2.357 2.553-2.894l4-2A1 1 0 0 1 11 6h2c.155 0 .308.036.447.106l4 2C18.522 8.643 19.999 9.652 20 11v10a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1");
}

.lfxipybne {
  d: path("M3 22a1 1 0 0 1 0-2h5v-7a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v7h5a1 1 0 0 1 0 2Zm11-6v-2h-4v2Zm0 4v-2h-4v2Z");
}

</style>

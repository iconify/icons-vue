<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uwqutdyno"/><path class="fad-bxasp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-truncate-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fad-bxasp {
  d: path("M21 5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2ZM9 17a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

.uwqutdyno {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.01 17a1 1 0 0 1 0 2H13a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Zm3.98 2a1 1 0 0 1 0-2H21a1 1 0 0 1 0 2Z");
}

</style>

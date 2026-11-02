<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fgp65gnit"/><path class="lv2153twu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-2-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fgp65gnit {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m6 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-8 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

.lv2153twu {
  d: path("M3 5h5a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m9 0h9a1 1 0 0 1 0 2h-9a1 1 0 0 1 0-2m2 6a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm4 0h3a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2M6 17a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm4 0h11a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2");
}

</style>

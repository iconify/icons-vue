<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lsxhw2bwk"/><path class="r9pi5jb8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-plus-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lsxhw2bwk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m15.84 5.153l5.5 9A4.5 4.5 0 0 1 17.5 21h-11a4.5 4.5 0 0 1-3.84-6.847l5.5-9a4.502 4.502 0 0 1 7.68 0");
}

.r9pi5jb8m {
  d: path("M13 11v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0");
}

</style>

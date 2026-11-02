<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bm5ylen5b"/><path class="fwp9lvbrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-forward-bulk-round" /></template>
<style>
.bm5ylen5b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m9.219 4.672l6 4a4 4 0 0 1 0 6.656l-6 4A4 4 0 0 1 3 16V8a4 4 0 0 1 6.219-3.328");
}

.cuyn6tgcc {
  fill: currentColor;
}

.fwp9lvbrl {
  d: path("M21 5v14a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0");
}

</style>

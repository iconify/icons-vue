<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hixl5jbzs"/><path class="wpr5olssl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:valve-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hixl5jbzs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11h4a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3h4a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-4a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3H3a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1");
}

.wpr5olssl {
  d: path("M15 4a1 1 0 0 1 0 2h-2v3a1 1 0 0 1-2 0V6H9a1 1 0 0 1 0-2ZM2 18v-8a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0m18 0v-8a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0");
}

</style>

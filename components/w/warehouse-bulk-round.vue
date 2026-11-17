<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="df-tkacyf"/><path class="xwoflwb9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.df-tkacyf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 22H8a5 5 0 0 1-5-5v-6.528A5 5 0 0 1 5.764 6l2.944-1.472c.694-.35 1.46-.53 2.236-.528h2.112a4.94 4.94 0 0 1 2.236.528L18.236 6A5 5 0 0 1 21 10.472V17a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22");
}

.xwoflwb9t {
  d: path("M7 16v-2a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v7a1 1 0 0 1-2 0v-4H9v4a1 1 0 0 1-2 0Zm2-1h6v-1a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1Z");
}

</style>

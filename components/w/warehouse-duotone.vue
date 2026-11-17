<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wr21qu14y"/><path class="nx1ffidtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nx1ffidtr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H6a2 2 0 0 1-2-2V9.236a2 2 0 0 1 1.106-1.789l4.472-2.236A2 2 0 0 1 10.472 5h3.056a2 2 0 0 1 .894.211l4.472 2.236A2 2 0 0 1 20 9.237V19a2 2 0 0 1-2 2zm-4 0v-7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v7m-8-5h8");
}

.wr21qu14y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 21H6a2 2 0 0 1-2-2V9.236a2 2 0 0 1 1.106-1.789l4.472-2.236c.277-.139.584-.211.894-.211h3.056c.31 0 .617.072.894.211l4.472 2.236A2 2 0 0 1 20 9.236V19a2 2 0 0 1-2 2");
}

</style>

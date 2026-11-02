<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="riis51qtn"/><path class="yxfnv8b6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tennis-ball-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.riis51qtn {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12");
}

.yxfnv8b6p {
  d: path("M16.686 9.093A6.486 6.486 0 0 0 18.6 17.2a1 1 0 0 1-1.2 1.6a8.4 8.4 0 0 1-2.503-2.998A8.4 8.4 0 0 1 14 12a8.4 8.4 0 0 1 .897-3.802A8.4 8.4 0 0 1 17.4 5.2a1 1 0 0 1 1.2 1.6a6.4 6.4 0 0 0-1.914 2.293m-7.583-.895A8.4 8.4 0 0 1 10 12a8.4 8.4 0 0 1-.897 3.802A8.4 8.4 0 0 1 6.6 18.8a1 1 0 0 1-1.2-1.6a6.4 6.4 0 0 0 1.914-2.293A6.4 6.4 0 0 0 8 12a6.4 6.4 0 0 0-.686-2.907A6.4 6.4 0 0 0 5.4 6.8a1 1 0 0 1 1.2-1.6a8.4 8.4 0 0 1 2.503 2.998");
}

</style>

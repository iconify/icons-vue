<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hyle18ydz"/><path class="lqgw2rbvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-bag-alt-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hyle18ydz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.lqgw2rbvs {
  d: path("M15.685 9.557a4 4 0 0 1-4.48 2.363A4 4 0 0 1 8 8a1 1 0 0 1 2 0a2 2 0 1 0 4 0a1 1 0 0 1 2 0a4 4 0 0 1-.315 1.557");
}

</style>

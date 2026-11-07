<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iuye57beg"/><path class="r30rsrzbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:timer-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iuye57beg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.964 13.721L9.573 4.33A9 9 0 0 1 11 4.054V4h-1a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2h-1v.054a9 9 0 0 1 4.618 1.913l1.675-1.674a.999.999 0 1 1 1.414 1.414l-1.674 1.675a9 9 0 0 1 1.637 8.045ZM6.714 5.714l12.572 12.572A9.001 9.001 0 1 1 6.714 5.714");
}

.r30rsrzbi {
  d: path("M2.293 2.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414ZM14 2a1 1 0 0 1 0 2h-1v1a1 1 0 0 1-2 0V4h-1a1 1 0 0 1 0-2Zm3.293 4.293l2-2a.999.999 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414-1.414");
}

</style>

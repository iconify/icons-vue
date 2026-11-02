<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q8ya4bz6e"/><path class="zxq3e0bqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playing-cards-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q8ya4bz6e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11a5 5 0 0 1 5-5h4a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5Z");
}

.zxq3e0bqt {
  d: path("M8 2h8a5 5 0 0 1 5 5v10a1 1 0 0 1-2 0V7a3 3 0 0 0-3-3H8a1 1 0 0 1 0-2m2.832 8.445l2 3a1 1 0 0 1 0 1.11l-2 3a1 1 0 0 1-1.664 0l-2-3a1 1 0 0 1 0-1.11l2-3a1 1 0 0 1 1.664 0M9.202 14L10 15.197L10.798 14L10 12.803Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w_vk5hwyd"/><path class="rp-cid_-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:spinner-rays-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rp-cid_-i {
  d: path("M13 6a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm3.707 2.707a.999.999 0 1 1-1.414-1.414l2-2a.999.999 0 1 1 1.414 1.414ZM18 13a1 1 0 0 1 0-2h3a1 1 0 0 1 0 2Zm-2.707 3.707a.999.999 0 1 1 1.414-1.414l2 2a.999.999 0 1 1-1.414 1.414ZM11 18a1 1 0 0 1 2 0v3a1 1 0 0 1-2 0Z");
}

.w_vk5hwyd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.707 7.293a.999.999 0 1 1-1.414 1.414l-2-2a.999.999 0 1 1 1.414-1.414ZM6 11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm1.293 4.293a.999.999 0 1 1 1.414 1.414l-2 2a.999.999 0 1 1-1.414-1.414Z");
}

</style>

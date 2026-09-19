<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyil1bcsj"/><path class="ttg5oj2on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-filter-2" /></template>
<style>
.jyil1bcsj {
  fill: currentColor;
  d: path("M7 17h14V3H7zm4-6a2 2 0 0 1 2-2h2V7h-4V5h4a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-2v2h4v2h-6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ttg5oj2on {
  fill: currentColor;
  d: path("M17 13h-4v-2h2a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2h-4v2h4v2h-2a2 2 0 0 0-2 2v4h6zm4-12H7c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 16H7V3h14zM1 21c0 1.1.9 2 2 2h16v-2H3V5H1z");
}

</style>

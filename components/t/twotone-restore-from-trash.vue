<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfp_wjb4s"/><path class="q03r1lbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-restore-from-trash" /></template>
<style>
.q03r1lbyy {
  fill: currentColor;
  d: path("M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6zm2-5V9h8v10H8zm7.5-10l-1-1h-5l-1 1H5v2h14V4zM10 18h4v-4h2l-4-4l-4 4h2z");
}

.qfp_wjb4s {
  fill: currentColor;
  d: path("M16 14h-2v4h-4v-4H8v5h8zm0 0V9H8v5l4-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>

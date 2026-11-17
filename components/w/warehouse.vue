<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iedectlic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse" /></template>
<style>
.iedectlic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H6a2 2 0 0 1-2-2V9.236a2 2 0 0 1 1.106-1.789l4.472-2.236A2 2 0 0 1 10.472 5h3.056a2 2 0 0 1 .894.211l4.472 2.236A2 2 0 0 1 20 9.237V19a2 2 0 0 1-2 2zm-4 0v-7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v7m-8-5h8");
}

</style>

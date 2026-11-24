<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqhoz9u-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:windmill-sharp" /></template>
<style>
.jqhoz9u-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 15l4 2l1 4H7l1-4zm-9 6h18M10 8a2 2 0 1 0 4 0a2 2 0 0 0-4 0m.586-1.414L7 3m6.414 3.586L17 3m-3.586 6.414L17 13m-6.414-3.586L7 13");
}

</style>

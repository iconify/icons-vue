<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyqian0hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rss-duotone-sharp" /></template>
<style>
.yyqian0hg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 18h.01M6 14a4 4 0 0 1 4 4m-4-8a8 8 0 0 1 8 8M6 6c6.627 0 12 5.373 12 12");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cidnrccwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-alt-duocolor" /></template>
<style>
.cidnrccwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m15 12l2 6c.369 1.107-.262 2.369-1 2l-4-2l-4 2c-.738.369-1.369-.893-1-2l4-12c.32-.961 1.68-.961 2 0z");
}

</style>

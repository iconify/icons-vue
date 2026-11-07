<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg9_k-j4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-off" /></template>
<style>
.cg9_k-j4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11 5l1-2l3 6l7 1l-3 3m-1.4 5.6L18 21l-6-3l-6 3l1-6l-5-5l6.125-.875M2 3l19 19");
}

</style>

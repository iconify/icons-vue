<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyxnv6bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-diagonal-duocolor-round" /></template>
<style>
.qyxnv6bcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 17a1 1 0 1 0 2 0a1 1 0 0 0-2 0m5-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m5-5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>

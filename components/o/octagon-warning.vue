<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khiexbcfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-warning" /></template>
<style>
.khiexbcfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h3c.64 0 1.36.36 2 1l3 3c.64.64 1 1.36 1 2v6c0 .64-.36 1.36-1 2l-3 3c-.64.64-1.36 1-2 1H9c-.64 0-1.36-.36-2-1l-3-3c-.64-.64-1-1.36-1-2V9c0-.64.36-1.36 1-2l3-3c.64-.64 1.36-1 2-1zm0 5v5m0 3h.01");
}

</style>

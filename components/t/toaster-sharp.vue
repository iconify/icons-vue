<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hb1fjkzjf"/><path class="kwfdxx8zc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toaster-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hb1fjkzjf {
  d: path("M7 11L7 9.7321C6.3819 9.3746 6.0013 8.7148 6.0013 8.0008C6.0013 6.8962 6.8967 6.0008 8.0013 6.0008C8.3832 6.0008 8.7572 6.1102 9.079 6.316C9.3967 4.9593 10.6066 4 12 4C13.3934 4 14.6033 4.9593 14.921 6.316C15.2428 6.1102 15.6168 6.0008 15.9987 6.0008C17.1033 6.0008 17.9987 6.8962 17.9987 8.0008C17.9987 8.7148 17.6181 9.3746 17 9.7321L17 11M2 11L22 11L22 20L2 20Z");
}

.kwfdxx8zc {
  fill: currentColor;
  d: path("M18.5 15.5C18.5 16.3284 17.8284 17 17 17C16.1716 17 15.5 16.3284 15.5 15.5C15.5 14.6716 16.1716 14 17 14C17.8284 14 18.5 14.6716 18.5 15.5Z");
  stroke: none;
}

</style>

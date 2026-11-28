<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="npwqn2b3v"/><path class="pelh9kbkx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:redo-dot-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.npwqn2b3v {
  d: path("M3 18.9998L3 17.9998C3 13.9534 5.3726 10.283 9.0622 8.6216C12.7518 6.9602 17.0727 7.6166 20.1025 10.2987L20.6054 10.7439M21 5.0002L21 11L15 11");
}

.pelh9kbkx {
  fill: currentColor;
  d: path("M11.2851 16.9998C11.2851 18.1044 12.1805 18.9998 13.2851 18.9998C14.3897 18.9998 15.2851 18.1044 15.2851 16.9998C15.2851 15.8952 14.3897 14.9998 13.2851 14.9998C12.1805 14.9998 11.2851 15.8952 11.2851 16.9998Z");
  stroke: none;
}

</style>

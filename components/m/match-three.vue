<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn1y2zb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:match-three" /></template>
<style>
.pn1y2zb2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 7.5h2.5L7 10l-2.5 6.5L2 10ZM2 10h5m3.75-2.5h2.5L14.5 10L12 16.5L9.5 10ZM9.5 10h5m3.75-2.5h2.5L22 10l-2.5 6.5L17 10ZM17 10h5");
}

</style>

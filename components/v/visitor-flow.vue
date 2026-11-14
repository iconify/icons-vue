<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9hvpbcpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:visitor-flow" /></template>
<style>
.j9hvpbcpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5H12v17H2.5Zm0 3.5H12M4.5 5.25h.01m2.24 0h.01M5 10.5h4.5m-4.5 3h3m5.5-1.5L21 5m-.5 3.25L21 5l-3.25.25M13.5 12h8M19 14l2.5-2l-2.5-2m-5.5 2l7.5 7m-3.25-.25L21 19l-.5-3.25");
}

</style>

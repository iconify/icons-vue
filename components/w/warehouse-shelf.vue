<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb1e3ccud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:warehouse-shelf" /></template>
<style>
.zb1e3ccud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21V3.5M20 21V3.5M4 9h16M4 15h16M4 20.5h16M6.5 5h4v4h-4Zm6.5 6h5v4h-5Z");
}

</style>

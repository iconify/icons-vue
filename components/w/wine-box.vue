<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m80v_ibln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wine-box" /></template>
<style>
.m80v_ibln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.6 17H3V3h14v7.7M6.5 17v2.5h3V17ZM8 19.5v2m0-15h4m4 7h5.5q0 4.5-2.75 4.5T16 13.5Zm2.75 4.5v3.5m-2 0h4");
}

</style>

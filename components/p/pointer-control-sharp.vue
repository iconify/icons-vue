<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwkdu4gcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pointer-control-sharp" /></template>
<style>
.mwkdu4gcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.52 8.05l6.46 3.65l.52.3l-.57.18l-2.26.74l-.57.18l-.26.54l-1.08 2.32l-.26.54l-.16-.58l-2.18-7.59L9 7.75zm-.02-3.3l2.5-2l2.5 2m-5 14.5l2.5 2l2.5-2M4.75 9.5l-2 2.5l2 2.5m14.5-5l2 2.5l-2 2.5");
}

</style>

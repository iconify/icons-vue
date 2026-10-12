<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clzwl3btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tea-glass-turkish-sharp" /></template>
<style>
.clzwl3btf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.75h8c0 2.75-1.75 4.25-1.75 6.5s2.25 4 2.25 6.75c0 1.75-1.5 2.5-4.5 2.5s-4.5-.75-4.5-2.5c0-2.75 2.25-4.5 2.25-6.75S8 5.5 8 2.75Zm1.25 9.5h5.5M3.75 20c1.5.9 4.25 1.25 8.25 1.25s6.75-.35 8.25-1.25");
}

</style>

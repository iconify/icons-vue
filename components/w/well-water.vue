<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcn6dfnxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:well-water" /></template>
<style>
.hcn6dfnxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5h5v14H7Zm-.75-2h6.5v2h-6.5Zm5.75 4h5v2m-9.5-6L3 2.5m1.5 19h10m2.5-8c1 1.5 1.5 2.25 1.5 3a1.5 1.5 0 0 1-3 0c0-.75.5-1.5 1.5-3Z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc3ys3b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pagination-sharp" /></template>
<style>
.tc3ys3b6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.25 10l-1.5 2l1.5 2m15.5-4l1.5 2l-1.5 2m-13-4h4v4h-4zm6.5 0h4v4h-4z");
}

</style>

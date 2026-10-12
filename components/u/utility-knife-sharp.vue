<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8vft3vck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:utility-knife-sharp" /></template>
<style>
.s8vft3vck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9 9.5l11.25-.75h1v8.5h-1L9 16.5Zm0 1.25H6.25l-3.5 4H9ZM12 13h6.5");
}

</style>

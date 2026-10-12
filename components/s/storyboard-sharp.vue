<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="potwi7g9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:storyboard-sharp" /></template>
<style>
.potwi7g9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h7.5v5H3zm10.5 0H21v5h-7.5zM3 13h7.5v5H3zm10.5 0H21v5h-7.5zM3 21h4.5m6 0H18");
}

</style>

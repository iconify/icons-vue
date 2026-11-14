<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2dbndb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sculpture-abstract" /></template>
<style>
.f2dbndb8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 17.5h10v4H7Zm2.5 0c-5.5-4.5-5-14 2-14c6 0 7.5 6.5 2.5 9C11 14 10 11 12.5 9");
}

</style>

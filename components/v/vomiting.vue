<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubhx3gt5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vomiting" /></template>
<style>
.ubhx3gt5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 17.75V14.5C5 13 4 11 4 9c0-3.5 2.75-6 6-6s5.75 2 5.75 5.25L17 11c0 .5-.25 1-.75 1h-.5v1.75c0 .75-.75 1.5-1.75 1.5h-1.5v2.5M13 7.5h.01M16 13.75c1.5 1 .5 3 2 4s.5 2.75 2 3.75m-2.75-9c1.75.75 1.5 2.5 3 3.5c.75.5 1 1.25 1.25 1.75");
}

</style>

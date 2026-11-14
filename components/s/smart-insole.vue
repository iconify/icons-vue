<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p340knnhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-insole" /></template>
<style>
.p340knnhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 8c2.25 0 3.75 1.75 3.75 4c0 2-2.25 3-2.5 5.25c-.25 2.5-1.5 4.25-3.5 4.25C8.5 21.5 7.5 20 7.5 18c0-2.25.75-3.75.75-6S10 8 12.5 8Zm-1.75 9.5h.01M9 6.75a4.75 4.75 0 0 1 6.5 0m-7.5-3a7.5 7.5 0 0 1 8.5 0");
}

</style>

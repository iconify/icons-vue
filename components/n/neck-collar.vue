<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ywn4lib8b"/><path class="au7x-7bxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:neck-collar" /></template>
<style>
.au7x-7bxl {
  fill: currentColor;
  d: path("M6.5 16.75h10v3.5h-10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ywn4lib8b {
  d: path("M5.122 13.939c-.429-1.07-.622-2.23-.622-3.439C4.5 6.25 7.75 3 12 3c4 0 7 2.75 7 6.75l1.5 3.5c.25.5-.1 1-.75 1h-.486");
}

</style>

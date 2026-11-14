<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-qqpeb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:massive-mimo" /></template>
<style>
.o-qqpeb8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h12v15H6Zm6 15v4m-3 0h6M9 6h.01M12 6h.01M15 6h.01M9 10h.01M12 10h.01M15 10h.01M9 14h.01M12 14h.01M15 14h.01");
}

</style>

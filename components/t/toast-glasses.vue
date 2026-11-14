<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncw3t7bhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:toast-glasses" /></template>
<style>
.ncw3t7bhu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5h7v3c0 2.5-1.5 4-3.5 4s-3.5-1.5-3.5-4ZM7 12v8m-2.5 0h5m4-15h7v3c0 2.5-1.5 4-3.5 4s-3.5-1.5-3.5-4Zm3.5 7v8m-2.5 0h5M12 2v1.25");
}

</style>

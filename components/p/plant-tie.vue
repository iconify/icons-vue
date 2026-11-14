<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv3g1fb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-tie" /></template>
<style>
.bv3g1fb3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5V7m0 0c0-2.5 2.5-4.5 5.5-4.5C17.5 5 15 7 12 7Zm0 6c-3-3-6-2-6 0s3 3 6 0Zm0 0c3-3 6-2 6 0s-3 3-6 0Zm-2.5 4.5L12 13l2.5 4.5");
}

</style>

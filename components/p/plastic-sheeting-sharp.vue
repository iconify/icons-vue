<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anev4c4hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plastic-sheeting-sharp" /></template>
<style>
.anev4c4hj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h12.5a2.5 3 0 0 1 0 6H6m0-6a2.25 3 0 1 0 0 6a2.25 3 0 1 0 0-6Zm1.5 6h12v11.25h-12Zm3 4h6m-6 3.75h6");
}

</style>

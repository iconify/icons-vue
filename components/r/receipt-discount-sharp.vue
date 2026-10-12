<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mupeepa7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:receipt-discount-sharp" /></template>
<style>
.mupeepa7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.75h12.5v18.5l-2.4-1.5l-2.45 1.5l-2.4-1.5l-2.4 1.5l-2.45-1.5l-2.4 1.5V2.75zm2 5h6.5m-6.5 3.5h4m-4 3.75h6.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2fafdc_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:receipt-long-sharp" /></template>
<style>
.o2fafdc_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 3.25h7v18l-1.58-1.2l-1.58 1.2l-1.59-1.2l-1.58 1.2l-1.59-1.2l-1.58 1.2v-18zm-5.5 0h15.5M9.25 7h5.5m-5.5 3h5.5m-5.5 3h5.5m-5.5 3h3.5");
}

</style>

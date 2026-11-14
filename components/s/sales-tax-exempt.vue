<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a18d6cc4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sales-tax-exempt" /></template>
<style>
.a18d6cc4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.395 15.603L2.5 11L8 4.5h9.585M21.5 8.485V17.5h-9.085M7.75 11h.01M12 8.5h.01m5.99 5h.01m-11.51 6l14-14");
}

</style>

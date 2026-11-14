<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr_7-r49u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:qr-code" /></template>
<style>
.dr_7-r49u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5h6v6h-6Zm11 0h6v6h-6Zm-11 11h6v6h-6Zm3-8h.01m10.99 0h.01M6.5 17.5h.01m7.99-3V17m3 .5h3m-6 3h3m3-6h.01");
}

</style>

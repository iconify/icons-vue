<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f40cxacmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:transfer-accept" /></template>
<style>
.f40cxacmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h13m-3.5-3.5L17 6l-3.5 3.5M20 12H7m3.5-3.5L7 12l3.5 3.5m4.25 2.5l2 2L21 15.75");
}

</style>

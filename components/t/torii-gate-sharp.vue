<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibnpe0b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:torii-gate-sharp" /></template>
<style>
.ibnpe0b6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.25h17.75l-.24.71l-.52 1.58l-.24.71H3.75l-.24-.71l-.52-1.58l-.24-.71zm2.75 3h2V10h7.5V6.25h2.5V10h2.5v2.5h-2.5v8.75h-2.5V12.5h-7.5v8.75h-2.5V12.5h-2.5V10h2.5V6.25z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5fcf1tkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:monorail-sharp" /></template>
<style>
.i5fcf1tkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.75v-1h12.5a6 6 0 0 1 6 6v2.5H2.75v-1Zm3 2.5h8.5m2.75 0h1.5M7 13.75v2.75m10-2.75v2.75m-14.25 0h18.5m-9.25 0v4.75");
}

</style>

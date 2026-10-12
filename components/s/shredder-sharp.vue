<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfbc4lm8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shredder-sharp" /></template>
<style>
.bfbc4lm8y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75h18.5v7H2.75zM6 12.25h12M6.75 8.75v-6h10.5v6m-10.5 7v5.5m3.5-5.5v3.75m3.5-3.75v5.5m3.5-5.5v3.75");
}

</style>

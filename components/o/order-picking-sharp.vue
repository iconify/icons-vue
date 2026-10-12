<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d05sv8x9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:order-picking-sharp" /></template>
<style>
.d05sv8x9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h10.5v15.5H2.75zm3 4h5m-5 3.25h5m-5 3.25h2.5m7.25-.75h5.75v8.75H15.5zm2.88 0v3");
}

</style>

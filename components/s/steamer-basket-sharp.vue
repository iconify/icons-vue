<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lco2l0b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:steamer-basket-sharp" /></template>
<style>
.lco2l0b2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.5a7.75 3.25 0 0 1 15.5 0Zm-1.5 3h18.5v10.75H2.75zm0 5.25h18.5");
}

</style>

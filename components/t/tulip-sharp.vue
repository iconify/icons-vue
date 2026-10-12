<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz5btfwfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tulip-sharp" /></template>
<style>
.dz5btfwfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 5.25L9.75 7.5L12 4.25l2.25 3.25l2.25-2.25v5.25a4.5 4.5 0 0 1-9 0ZM12 15v6.25m0 0c-.25-2.75-2-4.5-5-4.75c.25 2.75 2 4.5 5 4.75Z");
}

</style>

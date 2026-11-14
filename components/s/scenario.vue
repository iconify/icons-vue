<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q100fglzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scenario" /></template>
<style>
.q100fglzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 6.5h9.5l2.75 2l-2.75 2H9Zm6 6H5.5l-2.75 2l2.75 2H15Zm-3-10v4M9.75 4.75L12 2.5l2.25 2.25M12 10.5v2m0 4v5");
}

</style>

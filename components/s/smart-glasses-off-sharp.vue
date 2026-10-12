<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9c5mvbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-glasses-off-sharp" /></template>
<style>
.r9c5mvbib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 9.25h6.5v6.5h-6.5zm9 0h6.5v6.5h-6.5zm-2.5 2L12 9.366l1.25 1.884m-9-.25l-1.5-3.75m17 3.75l1.5-3.75m-6 5.25h3");
}

</style>

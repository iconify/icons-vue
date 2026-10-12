<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4v5zjb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:price-gun-sharp" /></template>
<style>
.s4v5zjb8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.75h12.25v7.5H9zm3.25 3.75h6M14 11.25h4.75l-.07 1l-.61 8l-.07 1h-4.25l-.07-1l-.61-8l-.07-1zm-1 4h-2.5v-4M3.17 6.88l.66-1.01l.42-.62H6v4.5H4.25l-.42-.62l-.66-1.01l-.42-.62z");
}

</style>

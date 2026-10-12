<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-fiv-brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:text-vertical-sharp" /></template>
<style>
.s-fiv-brr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3.75h7.5M8 3.75v6.75m-3.5 9.75l3.5-7l3.5 7m-5.75-2.5h4.5m7.5-14V20M15 17.25L17.75 20l2.75-2.75");
}

</style>

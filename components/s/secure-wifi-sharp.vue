<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1t_8ebac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:secure-wifi-sharp" /></template>
<style>
.m1t_8ebac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9a13 13 0 0 1 18.5 0M6 12.25a8.5 8.5 0 0 1 12 0m-9 3h6v6H9zm1.5 0V12.5h3v2.75");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1w_4n3sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pot-sharp" /></template>
<style>
.g1w_4n3sp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 10h15.5v11.25H4.25zm0 3h-1.5m17 0h1.5M3.75 7.5h16.5m-9.75 0V5h3v2.5");
}

</style>

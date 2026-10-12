<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alc1fpbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:page-landscape-sharp" /></template>
<style>
.alc1fpbln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75H10v12.5H2.75zm10 6.25h8.5v6.25h-8.5zm-1-11h2a5 5 0 0 1 5 5v2.25M16.5 9l2.25 2.25L21 9");
}

</style>

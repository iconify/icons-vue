<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzh1llbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:select-all-sharp" /></template>
<style>
.uzh1llbcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7V2.75H7m10 0h4.25V7m0 10v4.25H17m-10 0H2.75V17M10.5 2.75h3m-3 18.5h3M2.75 10.5v3m18.5-3v3m-14-6.25h9.5v9.5h-9.5z");
}

</style>

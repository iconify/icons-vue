<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8dnp5_eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tensile-test" /></template>
<style>
.m8dnp5_eg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5h4v11H3Zm14 0h4v11h-4Zm-10 4h10m-10 3h10m-7-12H3m2-2l-2 2l2 2m9-2h7m-2-2l2 2l-2 2");
}

</style>

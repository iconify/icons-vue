<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pembtm_7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tree-diagram-sharp" /></template>
<style>
.pembtm_7q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.75h5v4.5h-5zm5 2.25h3m2.5-5.5h-2.5v11h2.5m0-13.25h8v4.5h-8zm0 11h8v4.5h-8z");
}

</style>

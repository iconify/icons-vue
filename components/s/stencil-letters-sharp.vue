<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mli0-4b_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stencil-letters-sharp" /></template>
<style>
.mli0-4b_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75zm6 8.75l1.75-5m3 0l1.75 5m-6.5 0h6.5m-7.55 3l-.7 2m9.3-2l.7 2");
}

</style>

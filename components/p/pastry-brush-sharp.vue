<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3ltvp0-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pastry-brush-sharp" /></template>
<style>
.l3ltvp0-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 2.75h3.5v7h-3.5zm-2.75 7h9v3h-9zm1.5 3L8 21m4-8.25V21m3-8.25L16 21");
}

</style>

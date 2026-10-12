<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l12b8cbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paragraph-sharp" /></template>
<style>
.l12b8cbxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 3.75h-2.25a4.5 4.5 0 0 0 0 9H13Zm0 0v16.5m0-16.5h4.75m0 0v16.5");
}

</style>

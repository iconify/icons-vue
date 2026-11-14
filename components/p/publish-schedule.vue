<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rffusjbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:publish-schedule" /></template>
<style>
.rffusjbxb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.175 10.968L18.5 3L3 9.5L9 13v7.5l2.98-5.489m1.24-2.285l.764-1.407M9 13l9.5-10m-3.75 12.5h6.75v6h-6.75Zm0 2.75h6.75m-4.75-4.5v1.75m2.75-1.75v1.75");
}

</style>

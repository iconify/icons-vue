<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtth80bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parcel-stack-sharp" /></template>
<style>
.qtth80bzj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 14.5h17.5v6.75H3.25zm8.75 0v2.75m-6.25-8.5h12.5v5.75H5.75zm6.25 0v2m-3.5-8h7v6h-7zm3.5 0v2");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw5py35ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:melting-glacier-sharp" /></template>
<style>
.sw5py35ge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 5.25v-2.5h12.5v9a1.5 1.5 0 0 1-3 0a1 1 0 0 0-2 0v3.5h-3v-3.5a1 1 0 0 0-2 0a1.25 1.25 0 0 1-2.5 0Zm3 2.5l2.5-2.5m.5 12l1.35 1.747v.753a1.35 1.35 0 0 1-2.7 0v-.753z");
}

</style>

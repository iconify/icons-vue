<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nksjbpw6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zoom-lens-sharp" /></template>
<style>
.nksjbpw6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.75h2.5v6h-2.5zm3.75-2H14v1.5h7.25v7H14v1.5H5.25v-10zm3 0v10M6.5 18h11M8 16.5L6.5 18L8 19.5m8-3l1.5 1.5l-1.5 1.5");
}

</style>

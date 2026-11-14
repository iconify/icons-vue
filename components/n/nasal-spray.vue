<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu9x-otnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nasal-spray" /></template>
<style>
.pu9x-otnp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12.5h10v9h-10Zm2-3h6v3h-6Zm1.5 0h3l3-4.25L11.5 4Zm8.25-6.25l4-1.25M16 6h5m-5.75 2.75l4 1.25");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkc-am_zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sort-ascending-sharp" /></template>
<style>
.nkc-am_zp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6.5h4m-4 5.5h6.5m-6.5 5.5h9m4.5 1.75V4.75m-3.5 3.5l3.5-3.5l3.5 3.5");
}

</style>

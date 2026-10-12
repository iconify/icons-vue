<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov8xbc40j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:phone-vibrate-sharp" /></template>
<style>
.ov8xbc40j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3.75h8v16.5H8zm3 13.5h2m-7.75-8.5v6.5m-2.5-4.75v3m16-4.75v6.5m2.5-4.75v3");
}

</style>

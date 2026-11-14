<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnur4kzhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-lock-add" /></template>
<style>
.hnur4kzhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 20.8v.2h-10V10h10v5.2M4.75 10V6.75a2.75 2.75 0 0 1 5.5 0V10M7.5 13.5v4M18 15v6m-3-3h6");
}

</style>

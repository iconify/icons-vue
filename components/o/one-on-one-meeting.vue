<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slps2xb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:one-on-one-meeting" /></template>
<style>
.slps2xb5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5v7Q2.5 14 5 14h3.5m-2.75 0v4.5m-3 0h6m12.75-14v7q0 2.5-2.5 2.5h-3.5m2.75 0v4.5m-3 0h6M9.75 11h4.5M12 11v7.5m-1.75 0h3.5");
}

</style>

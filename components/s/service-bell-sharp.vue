<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugebc2brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:service-bell-sharp" /></template>
<style>
.ugebc2brg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5.25h4.5m-2.25 0v5M5.75 16.5a6.25 6.25 0 0 1 12.5 0Zm-2.5 0h17.5V21H3.25zM5 5.75l1.5 1.5M19 5.75l-1.5 1.5");
}

</style>

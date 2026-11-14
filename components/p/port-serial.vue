<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="redrd4b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:port-serial" /></template>
<style>
.redrd4b1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5h17l-2 9h-13Zm4 3h.01m2.99 0h.01m2.99 0h.01m2.99 0h.01M9 13.5h.01m2.99 0h.01m2.99 0h.01");
}

</style>

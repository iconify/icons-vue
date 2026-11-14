<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="emfwp8bnq"/><path class="xapqp6brg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mppt" /></template>
<style>
.emfwp8bnq {
  d: path("M5.5 2.5h13l2.5 10H3Zm6.5 0v10m-7.75-5h15.5m-11.25 5v8m-3 0h6m3 1L17 19l1.5 1.5l3-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xapqp6brg {
  d: path("M18.5 17.5h3v3");
}

</style>

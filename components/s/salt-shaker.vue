<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uttjp3bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:salt-shaker" /></template>
<style>
.uttjp3bpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 9h10l-.5 11h-9Zm1 0c0-4 1.5-5.5 4-5.5S16 5 16 9m-5.5-2.5h.01m2.99 0h.01");
}

</style>

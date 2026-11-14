<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxryjvrrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:recycle-off" /></template>
<style>
.xxryjvrrj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.817 6.844L12 4.75l3.5 6m.75-2.5l-.75 2.5l-1.14-.342M15.038 19H13.5m.76-.76l-.76.76l1.75 1.75M10.5 19H3.75l3.5-6m-2.5.75l2.5-.75l.75 2.5m-4.5-12l17 17");
}

</style>

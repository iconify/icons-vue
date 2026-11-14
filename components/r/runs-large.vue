<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg_bwfbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:runs-large" /></template>
<style>
.pg_bwfbdm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.55 18.5H5v-8l-3-1l2-5L8 3q2.5 3 5 0l4 1.5l2 5l-3 1v1.75M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>

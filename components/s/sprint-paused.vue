<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbh9p1b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sprint-paused" /></template>
<style>
.dbh9p1b-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 4.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM12.5 9l-2.75 4.75l3.25 2l-1 3.75m-2.25-5.75l-2 3.5l-3 .5M7.5 8.5L9.75 10l2.75-1l2.5 2.25L17.5 10m-15 1H5m-2.5 3.25h3m11 1.25V21m3.5-5.5V21");
}

</style>

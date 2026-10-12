<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bow80k2ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shower-head-sharp" /></template>
<style>
.bow80k2ww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 5.25H7l3.5 3.5m1.83-.53l4.59 1.81l.93.37l-.71.71l-4.28 4.28l-.71.71l-.37-.93l-1.81-4.59l-.37-.93l.71-.71l.38-.38l.71-.71zm2.52 7.68l1.05 1.05m.9.9l1.05 1.05m-1.6-4.4l1.05 1.05m.9.9l1.05 1.05m-1.6-4.4l1.05 1.05m.9.9l1.05 1.05");
}

</style>

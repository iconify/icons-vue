<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di6uwmbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rating-heart" /></template>
<style>
.di6uwmbpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11S8.25 8.75 8.25 6.5c0-1.25.75-2 2-2c.75 0 1.25.25 1.75 1c.5-.75 1-1 1.75-1c1.25 0 2 .75 2 2C15.75 8.75 12 11 12 11Zm-5.5 9.25S2.75 18 2.75 15.75c0-1.25.75-2 2-2c.75 0 1.25.25 1.75 1c.5-.75 1-1 1.75-1c1.25 0 2 .75 2 2c0 2.25-3.75 4.5-3.75 4.5Zm11 0s-3.75-2.25-3.75-4.5c0-1.25.75-2 2-2c.75 0 1.25.25 1.75 1c.5-.75 1-1 1.75-1c1.25 0 2 .75 2 2c0 2.25-3.75 4.5-3.75 4.5Z");
}

</style>

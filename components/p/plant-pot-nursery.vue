<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig101wb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-pot-nursery" /></template>
<style>
.ig101wb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 11h13L17 21.5H7Zm4.5 2.75l.25 5m3.75-5l-.25 5M12 11V8c-.25-3-2.25-5-5.25-5C6.75 6 9 8 12 8c.25-3.25 2.25-5.5 5.25-5.5c0 3-2 5.5-5.25 5.5");
}

</style>

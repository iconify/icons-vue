<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7_bbhoka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:off-grid" /></template>
<style>
.p7_bbhoka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 21.5l2.189-8.317m1.654-6.286L12 2.5l1.999 7.595m2.799 10.637L17 21.5m-6.6-15H19m-15.5 5h4.1m7.8 0h5.1m-11.25 5h3.3M3.5 3.5l17 17");
}

</style>

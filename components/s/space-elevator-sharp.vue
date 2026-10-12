<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhbh_m51m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-elevator-sharp" /></template>
<style>
.rhbh_m51m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.25a8.5 2.75 0 0 1 17 0Zm6-18.5h5v2.5h-5zm2.5 2.5v5m0 3v5.25m-1.5-8.25h3v3h-3z");
}

</style>

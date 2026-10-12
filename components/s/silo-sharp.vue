<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s78ju8_hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:silo-sharp" /></template>
<style>
.s78ju8_hh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.3 7.35L6.33 3.4l.3-.4l.3.4l3.02 3.95l.3.4H3zm-.3.4h7.25v13.5H3zm0 4h7.25m-7.25 4h7.25m3.5 5.5V12a3.75 3.25 0 0 1 7.5 0v9.25Zm0-5.5h7.5m-11-5.5l3.5 2.25");
}

</style>

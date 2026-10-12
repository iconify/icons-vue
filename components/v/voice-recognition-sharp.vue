<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsrhmyb0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:voice-recognition-sharp" /></template>
<style>
.nsrhmyb0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5V2.75H7.5m9 0h4.75V7.5m0 9v4.75H16.5m-9 0H2.75V16.5M7.5 10v4m3-6.5v9m3-7.5v6m3-4.25v2.5");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzl50xbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:upload-paused" /></template>
<style>
.uzl50xbcd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 15v3a2 2 0 0 0 2 2h6.25M12 15V3.5M7.5 8L12 3.5L16.5 8m0 7.5v5m3.25-5v5");
}

</style>

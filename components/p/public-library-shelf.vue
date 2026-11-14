<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf66mtirr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:public-library-shelf" /></template>
<style>
.cf66mtirr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h18v19H3ZM3 12h18M7 12V5.5m3.5 6.5V6.5M14 12l2.75-6M7.5 21.5V15m3.5 6.5V16m3.5 5.5V15");
}

</style>

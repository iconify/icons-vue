<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yosv5obmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mudroom" /></template>
<style>
.yosv5obmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h4.5v12.5l2.75 1.75v4.25H3Zm10 0h4.5v12.5l2.75 1.75v4.25H13ZM3 6.5h4.5m5.5 0h4.5");
}

</style>

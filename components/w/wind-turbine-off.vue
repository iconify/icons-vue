<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udy83cb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wind-turbine-off" /></template>
<style>
.udy83cb7f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 6.5h-5m5 0L18 2.25M15.5 6.5l2.5 4.25M15.5 6.5v5.1m0 7.8v2.1m-12-18l17 17");
}

</style>

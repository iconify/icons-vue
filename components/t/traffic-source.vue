<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqy27ijim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:traffic-source" /></template>
<style>
.aqy27ijim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 9h11v12.5h-11Zm0 3.5h11m-8.75-1.75h.01m2.24 0h.01M13 15.5h6m-6 3h4m-14.5-2h5.75m-2-2l2 2l-2 2M16 2.5V7m-2-2l2 2l2-2M3 3l5.25 5.25m-2.75 0h2.75V5.5");
}

</style>

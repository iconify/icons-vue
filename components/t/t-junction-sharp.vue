<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdddv4b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:t-junction-sharp" /></template>
<style>
.xdddv4b6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.75h18.5M2.75 12H8.5v9.25M21.25 12H15.5v9.25M2.75 8.38h2.5m5.5 0h2.5m5.5 0h2.5M12 15.5v3");
}

</style>

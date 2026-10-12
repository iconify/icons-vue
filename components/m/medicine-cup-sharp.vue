<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoyyy-psr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:medicine-cup-sharp" /></template>
<style>
.hoyyy-psr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.75h14.75l-.28 1.73l-1.69 10.54l-.28 1.73H6l-.28-1.73L4.03 8.48l-.28-1.73zm2 4H11M7.75 14h2.5m-2 3.25h3");
}

</style>

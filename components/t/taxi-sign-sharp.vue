<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljrodc9nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:taxi-sign-sharp" /></template>
<style>
.ljrodc9nu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 7.5h7.75l.21 1.23l.83 4.79l.21 1.23H6.25l.21-1.23l.83-4.79l.21-1.23zm-2 4h10.5m-7.75 0v3.25M12 11.5v3.25m2.5-3.25v3.25m-11 5.75c2-3.5 15-3.5 17 0");
}

</style>

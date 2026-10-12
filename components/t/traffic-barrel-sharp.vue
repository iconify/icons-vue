<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5q_ibj4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:traffic-barrel-sharp" /></template>
<style>
.k5q_ibj4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 3.75h8.5l.09 1l1.07 12.5l.09 1H6l.09-1l1.07-12.5l.09-1zM6.8 9h10.4M6.4 13.5h11.2M3.75 18.25h16.5v3H3.75z");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hn7tnnbwb"/><path class="vrx2xg14s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:membership-card" /></template>
<style>
.hn7tnnbwb {
  d: path("M2.5 5h19v14h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vrx2xg14s {
  d: path("m8 8.75l.882 2.036l2.209.21l-1.664 1.468l.483 2.165L8 13.5l-1.91 1.129l.483-2.165l-1.664-1.468l2.209-.21Zm5 1.5h5.5m-5.5 3.5h3.5");
}

</style>

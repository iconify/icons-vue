<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sai4wlrnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trail-map-sharp" /></template>
<style>
.sai4wlrnm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.4 5.75l3.45-1.5L9 3.75l1.15.48l3.7 1.54l1.15.48l1.15-.5l3.45-1.5l1.15-.5v14l-1.15.5l-3.45 1.5l-1.15.5l-1.15-.48l-3.7-1.54L9 17.75l-1.15.5l-3.45 1.5l-1.15.5v-14zm1.35 10.5L7 15.5m2-1.25l1.25-.5m2-.75l1-.75m1.5-1.25l.75-1m1-2.75l2.5 2.5m0-2.5l-2.5 2.5");
}

</style>

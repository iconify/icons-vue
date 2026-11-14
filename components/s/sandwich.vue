<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc_o6hbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sandwich" /></template>
<style>
.xc_o6hbff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.416 10.723l7.613-5.076a1.75 1.75 0 0 1 1.942 0l7.613 5.076A.93.93 0 0 1 21 11.5a.5.5 0 0 1-.5.5h-17a.5.5 0 0 1-.5-.5a.93.93 0 0 1 .416-.777M5 15.5h14a2 2 0 0 1 2 2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2a2 2 0 0 1 2-2m-1-1.75h16");
}

</style>

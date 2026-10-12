<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_0h11b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seti-dish" /></template>
<style>
.f_0h11b-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.76 14.24l8.48-8.48a6 3-45 0 1-8.48 8.48M13 10l-2.12-2.12m4.24 4.24V17m0 0l-3.37 4.25M15.12 17l3.38 4.25m-15.75 0h18.5M7.45 8.51A5.75 5.75 0 0 1 9.7 5.29M5.03 7.86a8.25 8.25 0 0 1 3.24-4.62");
}

</style>

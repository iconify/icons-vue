<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uelfr323z"/><path class="igr_6ub-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:occupancy-limit-sign" /></template>
<style>
.igr_6ub-b {
  d: path("M12.3 21.5H5v-17h9v7.3M11.75 13h.01m7.616.574l2.3 2.3v3.252l-2.3 2.3h-3.252l-2.3-2.3v-3.252l2.3-2.3ZM17.75 15.75v3.5m-1-2.75l1-.75");
}

.uelfr323z {
  d: path("M3 21.5v-19h13v8.3M2.5 21.5H12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

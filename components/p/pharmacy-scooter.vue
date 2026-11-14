<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dv6hivk1p"/><path class="ie41-iwkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pharmacy-scooter" /></template>
<style>
.dv6hivk1p {
  d: path("M3.5 17h14.75m.25 2l-2-16m-2 0h4M4 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm12.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ie41-iwkv {
  d: path("M3.5 9.5H11V17H3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

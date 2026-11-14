<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hqru8khag"/><path class="ovf4rgbwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:office-building" /></template>
<style>
.hqru8khag {
  d: path("M2.5 6h19v15.5h-19ZM6 6V3h5v3m4.5 0V2.5m-10 7h2m3.5 0h2m3.5 0h2M5.5 13h2m3.5 0h2m3.5 0h2");
}

.ovf4rgbwp {
  d: path("M10 21.5v-5h4v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

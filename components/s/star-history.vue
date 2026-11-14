<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uuroep7vz"/><path class="kic-98tsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:star-history" /></template>
<style>
.kic-98tsh {
  d: path("m6.5 14l.268-.422m.484-.759L10 8.5l3 2.5l2.832-3.068m1.628-1.764L19 4.5m-2 8l1.029 2.584l2.775.18l-2.14 1.777l.687 2.695L17 18.25l-2.351 1.486l.687-2.695l-2.14-1.777l2.775-.18Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuroep7vz {
  d: path("M3.5 3v17.5h8.1");
}

</style>

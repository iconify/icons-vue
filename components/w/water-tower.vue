<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="k7dc-rklw"/><path class="o09g9gxap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-tower" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k7dc-rklw {
  width: 14.5px;
  height: 8.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 3px;
}

.o09g9gxap {
  d: path("M4.75 7h14.5m-12.5 4v10.25M17.25 11v10.25M6.75 17h3.5m3.5 0h3.5M12 11.25v10");
}

</style>

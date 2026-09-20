<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h4br4z40f"/><path class="hrjx5ybsq"/><path class="e0fatccfd"/><path class="pkakcnb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:resistor-outline-bold" /></template>
<style>
.e0fatccfd {
  d: path("M18 12h4");
}

.h4br4z40f {
  d: path("M2 12h4");
}

.hrjx5ybsq {
  d: path("M6 8h12v8H6Z");
}

.pkakcnb0w {
  d: path("m8 14 3 -3 3 3 2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="dmjxi0bep"/><circle class="w7ips4bys"/><path class="dxneo4t6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:traffic-light-sharp" /></template>
<style>
.dmjxi0bep {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.75h10.5v18.5H6.75z");
}

.dxneo4t6j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01M12 16.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w7ips4bys {
  cx: 12px;
  cy: 7.25px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

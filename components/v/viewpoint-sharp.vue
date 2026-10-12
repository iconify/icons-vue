<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kcp3ym7ja"/><path class="a7xbknbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:viewpoint-sharp" /></template>
<style>
.a7xbknbyy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6.75h.01");
}

.kcp3ym7ja {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.41 20.25l4.18-4.75l.66-.75l.68.73l1.64 1.79l.68.73l.66-.75l2.43-2.75l.66-.75l.65.76l4.95 5.73l.65.76H2.75zM5 6.75C6.75 4.25 9.25 3 12 3s5.25 1.25 7 3.75c-1.75 2.5-4.25 3.75-7 3.75S6.75 9.25 5 6.75Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

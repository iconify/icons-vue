<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="k1qflxd-j"/><path class="cs185qb-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:triangle-obtuse-sharp" /></template>
<style>
.cs185qb-c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14h.01");
}

.k1qflxd-j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.99 4.99l7.27 12.77l.99 1.74H2.75l.99-1.74l7.27-12.77l.99-1.74z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

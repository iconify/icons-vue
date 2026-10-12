<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="fp00412ob"/><path class="yr8i2u48m"/><path class="gdd8ehb9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:return-label-sharp" /></template>
<style>
.fp00412ob {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25v-1.5h11.8l.719-.001l.451.561l4.16 5.2l1.201 1.5l-1.201 1.5l-4.16 5.2l-.451.561l-.719-.001H2.75v-1.5Z");
}

.gdd8ehb9d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 9.5h4.5a2.75 2.75 0 0 1 0 5.5H9m-.25-7.75L6.5 9.5l2.25 2.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yr8i2u48m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 12h.01");
}

</style>

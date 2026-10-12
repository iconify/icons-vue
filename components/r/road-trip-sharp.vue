<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mfpl-8p8z"/><path class="tsdqsjo2p"/><path class="inl-pr_7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:road-trip-sharp" /></template>
<style>
.inl-pr_7i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.25 12.75l-7.5 8.5m11-8.5l7.5 8.5m-9.25-6v1.25m0 2.75v2");
}

.mfpl-8p8z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10c-2-1.75-3-3-3-4.25a3 3 0 0 1 6 0C15 7 14 8.25 12 10Z");
}

.tsdqsjo2p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 5.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

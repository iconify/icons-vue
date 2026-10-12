<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="g2orrxpuo"/><path class="fvo3o1e-y"/><path class="ynqv78lsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-network-sharp" /></template>
<style>
.fvo3o1e-y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20.25h11.75v-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5v.75zm13.63-12.4l1.49-2.2m-1.49 5.5l1.49 2.2");
}

.g2orrxpuo {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ynqv78lsa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.25 4h.01M16.5 9.5h.01m3.74 5.5h.01");
}

</style>

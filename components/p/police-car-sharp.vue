<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wvxr25zen"/><path class="f35_vn1ti"/><path class="fsf8zjbnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:police-car-sharp" /></template>
<style>
.f35_vn1ti {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 16.25h.01m8.99 0h.01");
}

.fsf8zjbnk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 2.75h5.5v2.5h-5.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wvxr25zen {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 14.5L5.4 9.6l.466-1.356L7.3 8.25h9.4l1.434-.006L18.6 9.6l1.65 4.9v5H3.75v-1Zm2.75 5v1.75m11-1.75v1.75m-13.25-8h15.5");
}

</style>

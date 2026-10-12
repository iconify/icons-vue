<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="f0tz5eb6r"/><circle class="mo-_7fb8v"/><path class="pk64yxvcg"/><circle class="t0qyq4bin"/><circle class="zf4i7in1g"/><path class="n82e0kblr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:network-segment-sharp" /></template>
<style>
.f0tz5eb6r {
  cx: 5.5px;
  cy: 6.25px;
  r: 2.25px;
}

.mo-_7fb8v {
  cx: 5.5px;
  cy: 17.75px;
  r: 2.25px;
}

.n82e0kblr {
  d: path("M18.5 8.5v7");
}

.pk64yxvcg {
  d: path("M5.5 8.5v7M12 2.75v2m0 3.5v2m0 3.5v2m0 3.5v2");
}

.t0qyq4bin {
  cx: 18.5px;
  cy: 6.25px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zf4i7in1g {
  cx: 18.5px;
  cy: 17.75px;
  r: 2.25px;
}

</style>

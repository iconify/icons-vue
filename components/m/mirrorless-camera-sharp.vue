<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="slh4u-ijy"/><circle class="zz80vlb7c"/><path class="rbvsij3wx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mirrorless-camera-sharp" /></template>
<style>
.rbvsij3wx {
  d: path("M16.75 7.5v11.75");
}

.slh4u-ijy {
  d: path("M3.75 7.5h1l.5-1.37l.5-1.38h4.5l.5 1.38l.5 1.37h10v11.75H2.75V7.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zz80vlb7c {
  cx: 9.25px;
  cy: 13.25px;
  r: 3.5px;
}

</style>

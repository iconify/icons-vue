<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="tmwlrjguv"/><circle class="t5psuggxp"/><circle class="bwkxpguke"/><circle class="k24pirb5y"/><circle class="tl2wwdbnu"/><circle class="bi4vwgbyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:network-sharp" /></template>
<style>
.bi4vwgbyd {
  cx: 12px;
  cy: 12.5px;
  r: 2.75px;
}

.bwkxpguke {
  cx: 18.25px;
  cy: 5px;
  r: 2px;
}

.k24pirb5y {
  cx: 5.25px;
  cy: 18.5px;
  r: 2px;
}

.t5psuggxp {
  cx: 5px;
  cy: 5.5px;
  r: 2px;
}

.tl2wwdbnu {
  cx: 18.5px;
  cy: 18.75px;
  r: 2px;
}

.tmwlrjguv {
  d: path("m6.41 6.91l3.65 3.65m6.91-4.02l-3.21 3.85m-7.02 6.78l3.2-2.84m7.12 3.03l-3.08-2.95M7 5.42l9.25-.34m-9 13.46l9.25.17");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

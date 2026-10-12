<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="hep5mqb0m"/><rect class="qmh3n-c6g"/><rect class="lf6yi63ad"/><path class="b58_c5b3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:potato-plant" /></template>
<style>
.b58_c5b3h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 17.75h.01m9.99.5h.01m2.24 1h.01");
}

.hep5mqb0m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12V6.5m0 .5c0-2.25-1.5-3.75-4-4.25c0 2.5 1.5 4 4 4.25m0 2c0-2.25 1.5-3.75 4-4.25c0 2.5-1.5 4-4 4.25m-9.25 3h18.5M12 12v2.75m0 0C11 15 10 15.5 9.25 16M12 14.75c1 .25 2 .75 2.5 1.5");
}

.lf6yi63ad {
  width: 7px;
  height: 5px;
  x: 13.5px;
  y: 16.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.qmh3n-c6g {
  width: 6px;
  height: 4.5px;
  x: 3.5px;
  y: 15.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.25px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wneepcgok"/><path class="rt1gt-wju"/><path class="mjwg8v76c"/><path class="h3kayqbao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:straighten-photo" /></template>
<style>
.h3kayqbao {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.25 7.5a5.25 5.25 0 0 0-5-3.75m1.25-1l-1.25 1l1.25 1M2.75 21.25h18.5");
}

.mjwg8v76c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.4 10.72h.01");
}

.rt1gt-wju {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.24 14.14l4.2-2.94l1.92 2.97l1.73-.91l1.98 2.72");
}

.wneepcgok {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.6 6.51L17.87 8.7q1.71.36 1.35 2.07l-1.25 5.87q-.36 1.71-2.07 1.35L5.63 15.8q-1.71-.36-1.35-2.07l1.25-5.87q.36-1.71 2.07-1.35");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

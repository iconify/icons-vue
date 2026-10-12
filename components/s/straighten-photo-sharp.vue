<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bpaf5ebpu"/><path class="rt1gt-wju"/><path class="mjwg8v76c"/><path class="h3kayqbao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:straighten-photo-sharp" /></template>
<style>
.bpaf5ebpu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.6 6.51L17.87 8.7l1.71.36l-.36 1.71l-1.25 5.87l-.36 1.71l-1.71-.36L5.63 15.8l-1.71-.36l.36-1.71l1.25-5.87l.36-1.71z");
}

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

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

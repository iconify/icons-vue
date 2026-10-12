<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="r_5i0ab1b"/><path class="tx69zfbwr"/><path class="xcws4uzia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meteor-sharp" /></template>
<style>
.r_5i0ab1b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.15 12.54l2.2-1.83l1.15-.96l1.48.23l1.79.29l1.48.23l.54 1.4l.67 1.7L14 15l-.7 1.33l-1.1 2.09l-.7 1.33l-1.49.13l-2.77.24l-1.49.13l-1.06-1.06l-.63-.63L3 17.5v-4z");
}

.tx69zfbwr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 14h.01m2.49 3h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xcws4uzia {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 8.5L20.5 3m-3.75 9.25l4.5-4.5m-10-1l4-4");
}

</style>

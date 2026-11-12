<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="g6f3vgu_l"/><path class="k_2v7zbhf"/><path class="va-3p8pyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:recive-square-line-duotone" /></template>
<style>
.g6f3vgu_l {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7 12h7m0 0l-3 3m3-3l-3-3");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_2v7zbhf {
  stroke-linecap: round;
  d: path("M17 16V8");
}

.va-3p8pyw {
  d: path("M2 12c0-4.714 0-7.071 1.464-8.536C4.93 2 7.286 2 12 2s7.071 0 8.535 1.464C22 4.93 22 7.286 22 12s0 7.071-1.465 8.535C19.072 22 16.714 22 12 22s-7.071 0-8.536-1.465C2 19.072 2 16.714 2 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>

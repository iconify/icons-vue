<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wbdk3zbxt"/><path class="crgs_6jax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:party-popper" /></template>
<style>
.crgs_6jax {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 8h.01");
}

.wbdk3zbxt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.36 20.07l3.78-9.64q.36-.93 1.07-.22l5.58 5.58q.71.71-.22 1.07l-9.64 3.78q-.93.36-.57-.57M5.4 15.4l3.2 3.2m1.9-11.85c.75-1.5 2.25-1.75 1.75-4m5 10.75c1.5-.75 1.75-2.25 4-1.75m-5.75-8.5l-.75 2.25m6 3l-2.25.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

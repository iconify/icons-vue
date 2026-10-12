<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="n2vtrubcw"/><path class="cs185qb-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:triangle-altitude" /></template>
<style>
.cs185qb-c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14h.01");
}

.n2vtrubcw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.99 4.99l7.27 12.77q.99 1.74-1.01 1.74H4.75q-2 0-1.01-1.74l7.27-12.77q.99-1.74 1.98 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

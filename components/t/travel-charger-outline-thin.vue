<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oi1r4kf5x"/><path class="pdlat6brq"/><path class="k0hssvbpp"/><path class="x0i5t1jky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:travel-charger-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0hssvbpp {
  d: path("M15 3v3");
}

.oi1r4kf5x {
  d: path("M5 5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.pdlat6brq {
  d: path("M9 3v3");
}

.x0i5t1jky {
  d: path("M12 14v4h5v3");
}

</style>

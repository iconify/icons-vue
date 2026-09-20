<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f7i5iq2xf"/><path class="k9688w8mg"/><path class="ujtgx5bml"/><path class="hppiisbif"/><path class="wt9iv5biz"/><path class="olx65-bog"/><path class="exyd3ub4k"/><path class="oqfv9rb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ski-trip-duotone-thin" /></template>
<style>
.exyd3ub4k {
  d: path("m9 8 6 -6");
}

.f7i5iq2xf {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 19 6 -6 3 3 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hppiisbif {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k9688w8mg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 8 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.olx65-bog {
  d: path("m6 8 6 -6");
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.ujtgx5bml {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 8 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wt9iv5biz {
  d: path("m2 19 6 -6 3 3 5 -5 5 5");
}

</style>

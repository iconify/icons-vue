<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="k39urg--v"/><path class="yrana5b4o"/><path class="lio8itbog"/><path class="xgrfb-bqu"/><path class="vjqs2ebif"/><path class="k6x6uv-ap"/><path class="s09hy0b0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:venue-duotone-thin" /></template>
<style>
.earhjk-cy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k39urg--v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 6v13h14V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6x6uv-ap {
  d: path("M12 11v8");
}

.lio8itbog {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 11h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s09hy0b0y {
  d: path("M7 11h10");
}

.vjqs2ebif {
  d: path("M5 6v13h14V6");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.yrana5b4o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

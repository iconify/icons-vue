<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qps69pb2b"/><path class="b0s038b9v"/><path class="x6wxoo4ws"/><path class="lp2ig7bjb"/><path class="o46_3ibvz"/><path class="gzh4n16ws"/><path class="b6ubinbne"/><path class="ti0atfbnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:robot-arm-duotone-thin" /></template>
<style>
.b0s038b9v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.b6ubinbne {
  d: path("m6 12 6 -6h8v3.5");
}

.gzh4n16ws {
  d: path("M6 12v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lp2ig7bjb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 6v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o46_3ibvz {
  d: path("M3 20h6");
}

.qps69pb2b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ti0atfbnf {
  d: path("M17 6v3.5");
}

.x6wxoo4ws {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 12 6 -6h8v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vv6cu6ttg"/><path class="v9atpfbxg"/><path class="bj64t1bow"/><path class="afxv9_b8a"/><path class="oq5d88tuy"/><path class="x199_yb0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-duotone-thin" /></template>
<style>
.afxv9_b8a {
  d: path("M3 7h12a3 3 0 1 0 -3 -3");
}

.bj64t1bow {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h11a3 3 0 1 1 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oq5d88tuy {
  d: path("M3 12h15");
}

.v9atpfbxg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vv6cu6ttg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h12a3 3 0 1 0 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x199_yb0z {
  d: path("M3 17h11a3 3 0 1 1 -3 3");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nk8ojzxvh"/><path class="p0-5cbb5j"/><circle class="zopjch_2q"/><path class="itzdzgb-y"/><path class="k97ygbbpb"/><path class="cc2d90bow"/><path class="c4emy9bvw"/><path class="hz1k-gbkm"/><path class="c0vhcdb5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-path-line-duotone" /></template>
<style>
.c0vhcdb5e {
  stroke-linejoin: round;
  d: path("M6 11H6.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.c4emy9bvw {
  d: path("M13 11L19 11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.cc2d90bow {
  d: path("M13 5L19 5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hz1k-gbkm {
  stroke-linejoin: round;
  d: path("M6 5H6.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.itzdzgb-y {
  d: path("M5 14H19C20.6569 14 22 12.6569 22 11C22 9.34315 20.6569 8 19 8H5C3.34315 8 2 9.34315 2 11C2 12.6569 3.34315 14 5 14Z");
}

.k97ygbbpb {
  d: path("M5 8H19C20.6569 8 22 6.65685 22 5C22 3.34315 20.6569 2 19 2H5C3.34315 2 2 3.34315 2 5C2 6.65685 3.34315 8 5 8Z");
}

.nk8ojzxvh {
  d: path("M22 19H14M10 19H2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.p0-5cbb5j {
  d: path("M12 17V14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zopjch_2q {
  cx: 12px;
  cy: 19px;
  r: 2px;
}

</style>

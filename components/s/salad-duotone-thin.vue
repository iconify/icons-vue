<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lu8t8bbdh"/><path class="vd20ei7pe"/><path class="ykkw-8b6k"/><path class="ilf17yx9g"/><path class="k187sabpz"/><path class="kpavcn10r"/><path class="n5cv_rbxc"/><path class="o7aygz06s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:salad-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ilf17yx9g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m11 11 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k187sabpz {
  d: path("M2 11h20");
}

.kpavcn10r {
  d: path("M21 11a9 9 0 0 1 -18 0");
}

.lu8t8bbdh {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 11h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n5cv_rbxc {
  d: path("m5 11 4 -4 4 4");
}

.o7aygz06s {
  d: path("m11 11 4 -4 4 4");
}

.vd20ei7pe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 11a9 9 0 0 1 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ykkw-8b6k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m5 11 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>

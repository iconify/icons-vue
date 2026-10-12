<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lj4xjhsvk"/><path class="d6zyorbpm"/><circle class="mid5xcbxi"/><circle class="hm61d-bvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:steam-locomotive" /></template>
<style>
.d6zyorbpm {
  d: path("M5.25 8.25h2v2.5h-2Zm14 7l2 2.5");
}

.hm61d-bvp {
  cx: 14.75px;
  cy: 17.75px;
  r: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lj4xjhsvk {
  d: path("M2.75 15.25v-9a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v3h4.75v-3.5h3v3.5h.75a2 2 0 0 1 2 2v4Z");
}

.mid5xcbxi {
  cx: 6.25px;
  cy: 17.75px;
  r: 2.5px;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zebj0tbnr"/><path class="zlczmn02p"/><rect class="g0_m92v0c"/><path class="pdh51re_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prescription-pad" /></template>
<style>
.g0_m92v0c {
  width: 13.25px;
  height: 2.5px;
  x: 3.25px;
  y: 2.75px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pdh51re_w {
  d: path("M8 13.75V8h1.9a1.5 1.5 0 0 1 0 3H8m1.75 0l3 3m0-2.75L10 14m-2 2.25h6.5");
}

.zebj0tbnr {
  width: 13.25px;
  height: 13.5px;
  x: 3.25px;
  y: 5.25px;
  rx: 2px;
}

.zlczmn02p {
  d: path("M19.75 6.75v12.5a2 2 0 0 1-2 2H6.25");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="bug-6v0yw"/><path class="owwru7bmc"/><rect class="j5nsipxpg"/><path class="rr3d11bni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:security-token" /></template>
<style>
.bug-6v0yw {
  width: 11.5px;
  height: 18.5px;
  x: 6.25px;
  y: 2.75px;
  rx: 3.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j5nsipxpg {
  width: 5.5px;
  height: 6px;
  x: 9.25px;
  y: 11.75px;
  rx: 1.25px;
}

.owwru7bmc {
  d: path("M12 5.75a1.5 1.5 0 1 1 0 3a1.5 1.5 0 1 1 0-3");
}

.rr3d11bni {
  d: path("M10.75 14.75h.75m1 0h.75");
}

</style>

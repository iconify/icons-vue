<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j4m0w2b-t"/><path class="p3dq04btg"/><path class="i9hpnuf0x"/><path class="z0ud8rb7a"/><path class="ys-dg812g"/><path class="jkuojibnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:unpivot-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i9hpnuf0x {
  d: path("M18 2v5.5");
}

.j4m0w2b-t {
  d: path("M6 2v5.5");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.p3dq04btg {
  d: path("M12 2v5.5");
}

.ys-dg812g {
  d: path("M3 16h18");
}

.z0ud8rb7a {
  d: path("M9.5 10.5 12 13l2.5 -2.5");
}

</style>

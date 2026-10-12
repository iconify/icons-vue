<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pv3p7p0sl"/><path class="py6if5bsw"/><path class="caadc8bnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:retaining-wall" /></template>
<style>
.caadc8bnt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 10.75h.01m2.49 1.5h.01");
}

.pv3p7p0sl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3h1.5q.75 0 .75.75v13.5q0 .75.75.75h9.5q.75 0 .75.75v1.75q0 .75-.75.75h-17q-.75 0-.75-.75v-1.75q0-.75.75-.75h3q.75 0 .75-.75V3.75Q7.25 3 8 3");
}

.py6if5bsw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 7c2.75 0 5.25.5 8 1.5V15h-8Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

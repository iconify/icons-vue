<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="k7mg9plvr"/><path class="gmiy96biu"/><path class="ic-jxd84h"/><path class="gs7-71_dv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vinyl-play" /></template>
<style>
.gmiy96biu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 10.5a5.25 5.25 0 0 1 5.25-5.25m-.91 10.42a5.25 5.25 0 0 1-2.8-1.46");
}

.gs7-71_dv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.62 14.49l4.76 2.65q.87.49 0 .97l-4.76 2.65q-.87.49-.87-.51V15q0-1 .87-.51");
}

.ic-jxd84h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 10.5h.01");
}

.k7mg9plvr {
  cx: 10.5px;
  cy: 10.5px;
  r: 7.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>

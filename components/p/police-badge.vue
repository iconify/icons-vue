<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dklenmbsq"/><circle class="hjru5mbwv"/><circle class="ftdro6baa"/><circle class="jwub2_s5t"/><circle class="n2he7vj4w"/><circle class="rsnu82btf"/><circle class="s67nsxbky"/><circle class="peiq2hfxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:police-badge" /></template>
<style>
.dklenmbsq {
  d: path("m12.4 5.63l1.32 2.06q.41.63 1.15.66l2.44.12q.75.03.41.7l-1.13 2.16q-.34.67 0 1.34l1.13 2.16q.34.67-.41.7l-2.44.12q-.74.03-1.15.66l-1.32 2.06q-.4.63-.8 0l-1.32-2.06q-.4-.63-1.15-.66l-2.44-.12q-.75-.03-.41-.7l1.13-2.16q.34-.67 0-1.34L6.28 9.17q-.34-.67.41-.7l2.44-.12q.74-.03 1.15-.66l1.32-2.06q.4-.63.8 0");
}

.ftdro6baa {
  cx: 18.93px;
  cy: 8px;
  r: 1.25px;
}

.hjru5mbwv {
  cx: 12px;
  cy: 4px;
  r: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwub2_s5t {
  cx: 18.93px;
  cy: 16px;
  r: 1.25px;
}

.n2he7vj4w {
  cx: 12px;
  cy: 20px;
  r: 1.25px;
}

.peiq2hfxm {
  cx: 12px;
  cy: 12px;
  r: 1.75px;
}

.rsnu82btf {
  cx: 5.07px;
  cy: 16px;
  r: 1.25px;
}

.s67nsxbky {
  cx: 5.07px;
  cy: 8px;
  r: 1.25px;
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ujstiybic"/><path class="dj4rgmtcm"/><path class="cg0a9co7b"/><path class="ha190wb6v"/><path class="d27-dpb3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sunscreen-duotone-regular" /></template>
<style>
.cg0a9co7b {
  d: path("M7 21V8h10v13Z");
}

.d27-dpb3f {
  d: path("M9 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.dj4rgmtcm {
  fill: currentColor;
  d: path("M9 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ha190wb6v {
  d: path("M10 8V4h4v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ujstiybic {
  fill: currentColor;
  d: path("M7 21V8h10v13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

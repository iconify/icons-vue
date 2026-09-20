<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c-iufdcsb"/><path class="navc76bal"/><path class="gnn1wob3e"/><path class="umugi_b9i"/><path class="fmlaifbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:switch-case-duotone-regular" /></template>
<style>
.c-iufdcsb {
  fill: currentColor;
  d: path("m12 4 6 6 -6 6 -6 -6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fmlaifbpn {
  d: path("M12 16v4");
}

.gnn1wob3e {
  d: path("M18 10h3");
}

.navc76bal {
  d: path("m12 4 6 6 -6 6 -6 -6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.umugi_b9i {
  d: path("M3 10h3");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hlgur3d9q"/><path class="x7kl1kqgv"/><path class="zkgvk4bog"/><path class="laehq4zim"/><path class="sf079yb1a"/><path class="eylqpv51p"/><path class="oiu-3i4pj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:waypoint-duotone-bold" /></template>
<style>
.eylqpv51p {
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hlgur3d9q {
  fill: currentColor;
  d: path("M8 14a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.laehq4zim {
  d: path("M12 7.5V10");
}

.oiu-3i4pj {
  d: path("M12 18v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sf079yb1a {
  d: path("M8 14a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.x7kl1kqgv {
  fill: currentColor;
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zkgvk4bog {
  d: path("M12 2v3");
}

</style>

<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y4l98q7pn"/><path class="k74vnib1e"/><path class="fqjewfbna"/><path class="lna_zyjca"/><path class="tukmg9l1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:plumber-duotone-bold" /></template>
<style>
.fqjewfbna {
  d: path("M2 16a4 4 0 0 1 8 0");
}

.k74vnib1e {
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.lna_zyjca {
  d: path("m13 20 4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tukmg9l1f {
  d: path("M21.12 15.12a3 3 0 1 1 0 -4.24");
}

.y4l98q7pn {
  fill: currentColor;
  d: path("M3 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>

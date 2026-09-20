<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ipg5ngbqc"/><path class="ghgpbwtop"/><path class="prj9u5frn"/><path class="fdrffh_te"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:remote-control-outline-bold" /></template>
<style>
.fdrffh_te {
  d: path("M9 13h5");
}

.ghgpbwtop {
  d: path("M11 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ipg5ngbqc {
  d: path("M7 2v20h10V2Z");
}

.prj9u5frn {
  d: path("M9 10h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>

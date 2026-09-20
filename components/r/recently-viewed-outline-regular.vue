<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j534ltbcb"/><path class="m1mjigbsi"/><path class="d1zyr9bfc"/><path class="yb02nfmkn"/><path class="l5m2w6beb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:recently-viewed-outline-regular" /></template>
<style>
.d1zyr9bfc {
  d: path("M12 4v4");
}

.j534ltbcb {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.l5m2w6beb {
  d: path("M10 15.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.m1mjigbsi {
  d: path("M4 8h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yb02nfmkn {
  d: path("M7.3 13.79a5 5 0 0 1 9.4 0");
}

</style>

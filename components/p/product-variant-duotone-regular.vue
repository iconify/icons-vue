<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d8r3zz4mr"/><path class="lky3r4npi"/><path class="e--62-gxd"/><path class="j534ltbcb"/><path class="m1mjigbsi"/><path class="d1zyr9bfc"/><path class="im_j3hbaf"/><path class="abkn7obhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:product-variant-duotone-regular" /></template>
<style>
.abkn7obhy {
  d: path("M13.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.d1zyr9bfc {
  d: path("M12 4v4");
}

.d8r3zz4mr {
  fill: currentColor;
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e--62-gxd {
  fill: currentColor;
  d: path("M13.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.im_j3hbaf {
  d: path("M8.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.j534ltbcb {
  d: path("M3 6a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.lky3r4npi {
  fill: currentColor;
  d: path("M8.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
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

</style>

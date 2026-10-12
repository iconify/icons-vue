<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kqlqvtb_v"/><path class="pysxzsoqm"/><path class="gye4zw_nr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tpu-chip-sharp" /></template>
<style>
.gye4zw_nr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 2.75v3m3.25-3v3m3.25-3v3m-6.5 12.5v3m3.25-3v3m3.25-3v3M2.75 8.75h3m-3 3.25h3m-3 3.25h3m12.5-6.5h3m-3 3.25h3m-3 3.25h3");
}

.kqlqvtb_v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 5.75h12.5v12.5H5.75z");
}

.pysxzsoqm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 8.75h.01m3.24 0h.01m3.24 0h.01M8.75 12h.01M12 12h.01m3.24 0h.01m-6.51 3.25h.01m3.24 0h.01m3.24 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>

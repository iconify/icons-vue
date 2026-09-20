<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zp4rqbtqe"/><path class="ml5vh8o3m"/><path class="ngom1s3yg"/><path class="v7v_f9j5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:purge-cache-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ml5vh8o3m {
  d: path("M17 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ngom1s3yg {
  d: path("M20 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.v7v_f9j5h {
  d: path("M18 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zp4rqbtqe {
  d: path("M3 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>

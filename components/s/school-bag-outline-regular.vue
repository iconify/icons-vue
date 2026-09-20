<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fw2qxabom"/><path class="m-p3hbclp"/><path class="s6lrl6bmb"/><path class="xwfp38btc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:school-bag-outline-regular" /></template>
<style>
.fw2qxabom {
  d: path("M4 21V11a8 8 0 0 1 16 0v10Z");
}

.m-p3hbclp {
  d: path("M4 15h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s6lrl6bmb {
  d: path("M9 4v3");
}

.xwfp38btc {
  d: path("M15 4v3");
}

</style>

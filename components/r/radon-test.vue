<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c_n4t_9qd"/><path class="em8y3veek"/><path class="ed-0uxb4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:radon-test" /></template>
<style>
.c_n4t_9qd {
  d: path("m3.434 10.213l6.875-5.789a2.625 2.625 0 0 1 3.382 0l6.875 5.789a2.63 2.63 0 0 1 .934 2.008v6.654a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875v-6.654a2.63 2.63 0 0 1 .934-2.008");
}

.ed-0uxb4i {
  d: path("M12 14.5h.01");
}

.em8y3veek {
  fill: currentColor;
  d: path("m12.75 16l1.5 2.25a4.25 4.25 0 0 1-4.5 0l1.5-2.25a1.75 1.75 0 0 0 1.5 0m0-3l1.5-2.25a4.25 4.25 0 0 1 2 3.75h-2.5a1.75 1.75 0 0 0-1-1.5m-2.5 1.5h-2.5a4.25 4.25 0 0 1 2-3.75l1.5 2.25a1.75 1.75 0 0 0-1 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>

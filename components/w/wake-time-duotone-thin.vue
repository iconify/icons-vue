<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q82tmjh1i"/><path class="orxbb2h0a"/><path class="m1pvpub-n"/><path class="a5tuk3h7e"/><path class="zkgvk4bog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wake-time-duotone-thin" /></template>
<style>
.a5tuk3h7e {
  d: path("M4 10h16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m1pvpub-n {
  d: path("M7 10a5 5 0 0 1 10 0");
}

.orxbb2h0a {
  d: path("M3 20a3 3 0 0 1 0 -6h18a3 3 0 0 1 0 6Z");
}

.q82tmjh1i {
  fill: currentColor;
  d: path("M3 20a3 3 0 0 1 0 -6h18a3 3 0 0 1 0 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zkgvk4bog {
  d: path("M12 2v3");
}

</style>

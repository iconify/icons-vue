<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n0n63pb2v"/><path class="lh_8lcb-x"/><path class="juej44_6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:push-gateway-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.juej44_6j {
  d: path("M9.5 7.5 12 10l2.5 -2.5");
}

.lh_8lcb-x {
  d: path("M12 4v6");
}

.n0n63pb2v {
  d: path("M4 15v4h16v-4");
}

</style>

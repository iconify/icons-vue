<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d8abqfbpc"/><path class="h_c4fk0bb"/><path class="l3hfq7bhw"/><path class="gjmq94baq"/><path class="lfyekl_xx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:map-scale-outline-thin" /></template>
<style>
.d8abqfbpc {
  d: path("M3 11h18");
}

.gjmq94baq {
  d: path("M15 11v4");
}

.h_c4fk0bb {
  d: path("M3 11v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3hfq7bhw {
  d: path("M9 11v4");
}

.lfyekl_xx {
  d: path("M21 11v6");
}

</style>

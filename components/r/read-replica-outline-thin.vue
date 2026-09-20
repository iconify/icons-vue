<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y76hd_85j"/><path class="x0l-yf_vd"/><path class="rq7zt3oij"/><path class="ebn0uqb8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:read-replica-outline-thin" /></template>
<style>
.ebn0uqb8o {
  d: path("M11 12h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rq7zt3oij {
  d: path("M14.5 10a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-3.5a2 2 0 0 1 -2 -2Z");
}

.x0l-yf_vd {
  d: path("M2 9h9");
}

.y76hd_85j {
  d: path("M2 6a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>

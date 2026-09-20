<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y76hd_85j"/><path class="tc8fh3off"/><path class="f2kvp6bqh"/><path class="cys9dsbbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:partition-prune-outline-thin" /></template>
<style>
.cys9dsbbm {
  d: path("m20 9 -4 4");
}

.f2kvp6bqh {
  d: path("m16 9 4 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tc8fh3off {
  d: path("M14 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.y76hd_85j {
  d: path("M2 6a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>

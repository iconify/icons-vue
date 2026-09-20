<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uqqniu6bc"/><path class="j2-drqnzq"/><path class="lp-jzobeh"/><path class="lvrweqtce"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:marathon-outline-thin" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2-drqnzq {
  d: path("m13 7 -4 4 4 4");
}

.lp-jzobeh {
  d: path("M9 11H5");
}

.lvrweqtce {
  d: path("m13 15 4 4");
}

.uqqniu6bc {
  d: path("M11 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>

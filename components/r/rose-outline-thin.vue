<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yoftwf7ei"/><path class="gr1zxddav"/><path class="e2nq-yvbg"/><path class="ueskbccpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rose-outline-thin" /></template>
<style>
.e2nq-yvbg {
  d: path("M12 15v6");
}

.gr1zxddav {
  d: path("M9 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ueskbccpe {
  d: path("M4 19c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

.yoftwf7ei {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
}

</style>

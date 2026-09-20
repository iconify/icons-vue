<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c5icmybsm"/><path class="ozx545qvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:signed-release-outline-thin" /></template>
<style>
.c5icmybsm {
  d: path("m4 12 6 -6h10v12H10Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ozx545qvz {
  d: path("m11 12 2 2 4 -4");
}

</style>

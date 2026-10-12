<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rit0sxbrt"/><path class="l6i-tfn6u"/><rect class="q2-_x6b_z"/><path class="oxw7akivi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prompt-chain" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6i-tfn6u {
  d: path("m5.75 5l1.5 1.5L5.75 8m2.5 1.75v5.5a2 2 0 0 0 2 2");
}

.oxw7akivi {
  d: path("m13.25 16l1.5 1.5l-1.5 1.5");
}

.q2-_x6b_z {
  width: 11px;
  height: 6.5px;
  x: 10.25px;
  y: 14.25px;
  rx: 2px;
}

.rit0sxbrt {
  width: 11px;
  height: 6.5px;
  x: 2.75px;
  y: 3.25px;
  rx: 2px;
}

</style>

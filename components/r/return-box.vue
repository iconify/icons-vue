<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xnw6rezjr"/><path class="a8kdvk-nl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:return-box" /></template>
<style>
.a8kdvk-nl {
  d: path("M3.25 14.25h17.5m-10-3.5v3.5h2.5v-3.5m4-2.5v-.5a2.5 2.5 0 0 0-2.5-2.5h-9.5m2.5-2.5l-2.5 2.5l2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xnw6rezjr {
  width: 17.5px;
  height: 10.5px;
  x: 3.25px;
  y: 10.75px;
  rx: 2px;
}

</style>

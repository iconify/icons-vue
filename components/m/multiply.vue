<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kxq9ww4ym"/><path class="jmo57ab0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:multiply" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jmo57ab0a {
  d: path("m9 9l6 6m0-6l-6 6");
}

.kxq9ww4ym {
  width: 16.5px;
  height: 16.5px;
  x: 3.75px;
  y: 3.75px;
  rx: 2.5px;
}

</style>

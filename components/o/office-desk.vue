<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a5x8i9byg"/><path class="kafho6mpr"/><rect class="aka4f529a"/><path class="yf9gq71tw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:office-desk" /></template>
<style>
.a5x8i9byg {
  width: 18.5px;
  height: 3.25px;
  x: 2.75px;
  y: 6.75px;
  rx: 1.25px;
}

.aka4f529a {
  width: 8px;
  height: 9px;
  x: 12.5px;
  y: 12.25px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kafho6mpr {
  d: path("M5 10v11.25");
}

.yf9gq71tw {
  d: path("M15.25 15h2.5m-2.5 3.5h2.5");
}

</style>
